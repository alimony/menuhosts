# MenuHosts

This is currently just a concept.

It would be nice with an item in the menubar that enables and disables entries in `/etc/hosts`:

![MenuHosts screenshot](/menuhosts.png)

This application could have its own section in the hosts file and not interfere with anything else:

```
<other host entries>

### BEGIN MENUHOSTS ###

127.0.0.1        mylittleserver.local
127.0.0.1        someserver.local
123.456.789.123  example.com
123.456.789.123  example.org
127.0.0.1        example.net

### END MENUHOSTS ###

<more host entries>
```

Well, that’s all I have at the moment. If you’re interested in writing this application, please get in touch – maybe we can collaborate in some way:

markus@polyscopic.works
