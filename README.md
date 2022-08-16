# Graduation-Project

Easy shopping is an application that allows us to compare the sum
of the prices on the labels with the total price at the checkout so
that we do not overpay. The photo of the product label is taken
and sent to the API we wrote through the retrofit library. The
photo coming to the API is sent to the Amazon S3 service and
saved in the bucket. After detecting the text in the photo in
Amazon Rekognition, the texts found are sent to the API. The
required product and price information is filtered in the API. The
filtered text is taken with the help of a retrofit and displayed to the
user on the mobile device.

We are doing the graduation project by two people. We develop
the application in Kotlin language. In the project we used the
Amazon Rekognition API to get the image analysis. We wrote the
API service of the project with C# Asp.Net 5.0. We installed the
API we wrote by opening the virtual machine using Amazon's EC2
service and installing the IIS Service in it. We used the Retrofit
library to communicate with the API we wrote through our
application. We used GSON for JSON Parsing operations with
Retrofit.


- MVVM
- Retrofit
- Data Binding
- Fragments
- RecyclerView
- Navigation Component
- AWS Rekognition API
- AWS EC2
- AWS S3
- C# Asp.Net

<video src='https://user-images.githubusercontent.com/58865367/184962387-629253fe-3d8d-4913-b217-0c9824d6802e.mp4' width=180/>



