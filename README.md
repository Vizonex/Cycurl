# Cycurl
Cython Bindings for Libcurl Inspired by PyCurl made to be faster than synchronous httpx and requests, this library is in the making and is Coming Soon...

# Plans And Goals With This Library
- Build all static Files for windows with almost everything supported such as openssl , http2/3 protocols, ipv6 support on x86, x64, amd64,    etc...  My Reasoning for adding all precompiled binaries is simple,
  1. nobody enjoys to compiling these themselves
  2. They're very annoying and compiling the static version of all of these builds can be a nightmare!
  3. A Simple PIP install is all that should ever be required Escpecially on Windows!

- Unix Versions should be easy as day to compile as well. 
- The File should be small enough so that pyinstaller will not create a huge executable full of bulk.
- Make it so that custom python sockets such as proxy chains and tor can all be forwarded.
