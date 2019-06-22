# learnDocker

learning docker ...

<a href="https://gist.github.com/bradtraversy/89fad226dc058a41b596d586022a9bd3">traversy media gist</a>

sync folder with container

<pre>
docker container run -d -p 8080:80 -v $(pwd):<code>path to web folder of container</code> --name <code>container name</code> <code>image name</code>
</pre>

Demo (nginx):

<pre>
docker container run -d -p 8080:80 -v $(pwd):/usr/share/nginx/html --name nginx-website nginx
</pre>
