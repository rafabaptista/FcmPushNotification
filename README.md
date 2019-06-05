# FcmPushNotification
This project is an example of how to use the Firebase Cloud Messaging (FCM) from google

#How to send Push Notification (check .help/howToSendPushNotification)
1) Http POST url: https://fcm.googleapis.com/fcm/send
2) Headers:
    Content-Type = application/json
    Authorization = key=<your_Firebase_server_key>
3) Body (jSon for THIS project that I'' using):
    {
     "to" : "<user_FCM_token>",
     "data": {
     	"title": "<text for Notification Title>",
     	"message": "<text for Notification BODY>"
     }
    }
