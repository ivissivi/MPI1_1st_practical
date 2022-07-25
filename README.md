# MPI1_1st_practical
## Pictures fragment
### Displaying pictures
Images that were taken by the user are being displayed in a slider view and are being cycled through automatically. Right after the image is captured, the thumbnail changes to the most recent image, that was captured by the user.
![picture1](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture1.jpg?raw=true)
![picture2](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture2.jpg?raw=true)
### Capturing images
For image capturing there is a “TAKE AN IMAGE” button. Images are saved to internal storage and uploaded to Firebase. If everything goes right, a toast message of “Upload successful” appears and the image can be located in the Firebase storage.
![picture3](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture3.jpg?raw=true)
![picture4](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture4.jpg?raw=true)
## Audio fragment
### Displaying recordings
Recordings that were recorded by the user are displayed in a list view. Each item contains the full name of the file from storage. File name is generated randomly by adding the current time in milliseconds to the string of the file name.
![picture5](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture5.jpg?raw=true)

For audio recording there is a “RECORD AUDIO” button. To start recording, the use must simply click it once and in order to stop the recording user must click the button again. Recordings are saved to internal storage of the device under /Music.
![picture6](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture6.jpg?raw=true)
![picture7](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture7.jpg?raw=true)

## Firebase
### Firebase Cloud Storage
Images that are captured by the user are uploaded to the database under “uploads”.
![picture9](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture9.png?raw=true)
### Firebase Realtime Database
Image URLs are uploaded to a realtime database under uploads.
![picture10](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture10.png?raw=true)
### Firebase Analytics
Buttons that are clicked by the user are logged in the Firebase analytics and grouped by the event name.
![picture11](https://github.com/ivissivi/MPI1_1st_practical/tree/master/preview/picture11.png?raw=true)
