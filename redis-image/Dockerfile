#Use an existing docker image as a base
FROM alpine

# Download and install a dep
RUN apk add --update redis

#Tell the image what do when it starts
CMD ["redis-server"]
