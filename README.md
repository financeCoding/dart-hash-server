An example client/server dart application that uses the [LUCA framework][LUCA] and [dart http server][HTTPserver]. The server is based on the components found in [dart/samples/chat/][HTTPserver]. This application shows how one could create a client application that posts json data to a http server that then makes some calculations (in this example its [hash values][HASHES]) and returns to the client. 

Build & Run this application
----------------------------

    git clone git://github.com/financeCoding/dart-hash-server.git
    cd dart-hash-server
    git submodule update --init
    ./run.sh

Before running you might need to adjust the location of the frog and dart locations in the `run.sh`. Open the url thats gets displayed in the console in chrome. The default address should be `http://127.0.0.1:8123/`

[LUCA]: https://github.com/LUCA-Studios-LLC/LUCA-UI-Framework-for-Dart
[HTTPserver]:https://code.google.com/p/dart/source/browse/#svn%2Fbranches%2Fbleeding_edge%2Fdart%2Fsamples%2Fchat
[HASHES]:https://github.com/financeCoding/dart-hash-server/tree/master/src/HashLib

