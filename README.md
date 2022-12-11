# DemoVideoStream

#Project Is developed using dot net core 6 MVC

#Daily.co library is used by adding client side library with unpkg format

#May cause client server side error  this can be solved using https:// url

#sign in with
https://dashboard.daily.co/
#create your room
#using Room Menu shown in image
![image](https://user-images.githubusercontent.com/25446922/206901463-948dc0c3-2c5e-4cc5-8653-9165de1314ae.png)
#your URL
#get your url using "Copy Link To Clipboard" as shown in image below from room

![image](https://user-images.githubusercontent.com/25446922/206901665-84fd98bb-91e7-491e-b057-58da52041a54.png)


#code for enabling video call and video stream

<html>
  <script crossorigin src="https://unpkg.com/@daily-co/daily-js"></script>
  <body>
    <script>
      callFrame = window.DailyIframe.createFrame({
        showLeaveButton: true,
        showFullscreenButton:true,
        userName:"abhijeet",
            iframeStyle: {
                position: 'fixed',
                top: '0',
                left: '0',
                width: '100%',
                height: '100%',
            },
        });

      callFrame.join({ url: 'https://videoconferencelearn.daily.co/NAQAep5UgD72Juodgael' });
    </script>
  </body>
</html>
