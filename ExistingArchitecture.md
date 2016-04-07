# Current architecture of ubuntu touch

![Ubuntu touch Architecture](ubuntu_touch_architecture.png)

![Container Architecture](container.png)

Stripping mir/unity stuffs as well as ubuntu libhybris, and installing upstream libhybris + kwin/wayland + plasma-mobile stuffs. Installing our own libhybris makes compat stuff available in android container effectively useless. As compat stuff is removed from upstream long ago.
