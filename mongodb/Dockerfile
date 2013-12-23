FROM		wembli/centos64:latest
ADD		mongodb.repo /etc/yum.repos.d/mongodb.repo
RUN		yum install -y mongo-10gen mongo-10gen-server
ADD		mongod.conf /etc/mongod.conf
EXPOSE		27017
CMD		["-f","/etc/mongod.conf"]
ENTRYPOINT	["/usr/bin/mongod"]
