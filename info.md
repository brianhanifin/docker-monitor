# Docker Monitor

The Docker monitor allows you to monitor statistics and turn on/off containers. The monitor can connected to a daemon
through the url parameter. When home assistant is used within a Docker container, the daemon can be mounted as follows
`-v /var/run/docker.sock:/var/run/docker.sock`. The monitor is based on [Glances](https://github.com/nicolargo/glances)
 and [ha-dockermon](https://github.com/philhawthorne/ha-dockermon) and combines (in my opinion the best of both
 integrated in HA :)).

Install and configuration information can be found in the [documentation](https://github.com/Sanderhuisman/docker-monitor).
