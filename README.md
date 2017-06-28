# socketio_sample
web socketIO server and client with python.
dependce@socketIO-client 0.7.2 but not socketIO-client-2 0.7.2.
you can run server app in socketio.run(app, debug=True) with debug infomations.
mybe you need modify the client source to socketIO = SocketIO('127.0.0.1', 5000) when
you are behind a proxy intranet.
