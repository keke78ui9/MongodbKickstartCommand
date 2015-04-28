# MongodbKickstartCommand
one click command that will start mongodb to your enviroment


> :: this command require mongo db file at C drive.
> :: taks will be remove the mongo db service, and add mongo db to windows service.
> sc delete "MongoDB"
> cd \
> move C:\mongodb-win32-* C:\mongodb
> md data
> md data\db
> md mongodb\log
> echo logpath=C:\mongodb\log\mongo.log > C:\mongodb\mongod.cfg
> C:\mongodb\bin\mongod.exe --config C:\mongodb\mongod.cfg --install
> net start mongodb
> pause
