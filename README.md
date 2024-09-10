Real-Time Chat Application



Overview:
This is a real-time chat application built using Flask and Socket.IO. The application allows users to create and join chat rooms, send messages, and receive updates in real-time.

Features: User authentication, Room creation, Message broadcasting, Real-time updates, Scalable and performant architecture


Technical Details
-The application uses Flask as the web framework and Socket.IO for real-time communication.
-The generate_unique_code function generates a unique 4-character code for each new room.
-The rooms dictionary stores information about each room, including its members and messages.
-The @socketio.on decorators handle Socket.IO events, such as connecting, disconnecting, and sending messages.
