FROM		wembli/centos64:latest
ADD		redis.conf /etc/redis.conf
RUN		yum install -y redis
EXPOSE		6379
CMD		["/etc/redis.conf"]
ENTRYPOINT	["/usr/sbin/redis-server"]
