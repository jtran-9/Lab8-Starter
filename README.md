# Lab8-Starter

### Lab Participant(s)
Justin Tran

### Github Pages
[Recipe Application](https://jtran-9.github.io/Lab8-Starter/)

### Graceful Degradation and Service Workers
The point of graceful degradation is to make sure that web applications remain fully functional when certain technologies are not supported by the user's device. This is what service workers aim to do as their purpose is to be capable of loading in data in offline environments by caching resources. Because of this, even when the user's device does not have access to the network, if their device had already loaded this page already and stored all the resources in the cache, the service workers can just retrieve that information and load those resources before trying to access the network. By using service workers, web applications can still be accessible even during offline environments by retrieving already cached resources and loading them onto the page. Although, since the device is offline, it cannot retrieve any new resources without being connected to the network. Therefore, this is an example of graceful degradation integration as it helps provide a simpler version of the application when certain things are lacking on the user's device.

### pwa.png
![pwa screenshot](pwa.png)
