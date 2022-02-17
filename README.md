# Amazon-Go
Computer Vision, Deep Learning

https://user-images.githubusercontent.com/91654378/154535651-e4c2a480-4c4d-428a-b280-4f2b536a58ad.mp4

# About

---

Amazon Go is the first store of its kind where you don’t need to check out from the store. Customers can simply enter the store using the Amazon Go app to browse and take the products they want and can leave. How cool is that? Amazon Go store is partially automated where customers don’t need to stand in a queue for check-out counters.

Amazon Go technology can detect when products are taken or returned to the shelves and keeps track of them in your virtual cart.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Amazon-Go/blob/main/images/img1.jpg" />

# How does it Works ?

---

To get started, you just need an Amazon account and a smartphone. You have to scan the app as you enter the store. You can then put away your phone and begin shopping - picking up items, putting them in a basket or in bags (without needing to scan each item). You can just simply walk out when you're finished. The money debits automatically from your amazon wallet.

You don't need to check out and you can replace items at any time.

# Technologies used
# 1. Computer Vision

---

Computer Vision is a field of study that seeks to develop techniques to help computers “see” and understand the content of digital images such as photographs and videos. For example, we can use a trained computer to identify fruits. The images will be captured by a digital camera and fed to our rained computer. Our trained computer will use either machine learning or deep learning to identify fruits in those images.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Amazon-Go/blob/main/images/img2.png" />

# Computer Vision has three objectives:
# 1.1 Object Classification

---

Object classification is related to computer vision and image processing that deals with detecting instances of semantic objects of a certain class in digital images and videos. Imagine we have an image of vegetables and fruits on a shelf. Now, our algorithm will classify each object into fruit a=or vegetable.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Amazon-Go/blob/main/images/img3.png" />

# 1.2 Object Identification

---

Object identification refers to identifying the unique characteristics of an object. Instead of classifying objects into fruit and vegetable only, the algorithm tries to find which fruit or vegetable is present in our image.

# 1.3 Object Tracking

---

Videos are just a bunch of images. If we pass each image to our computer vision algorithm, then our algorithm might think that each

person in all images are different, but they are not.

Like in following scenario, two cameras can see the same person, but watch camera will identify the same person as different person if object tracking is not used.

Thus with object tracking we can track each object in frame so that the same person doesn't get registered as new person.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Amazon-Go/blob/main/images/img4.png" />

# 2. Sensor Fusion

---

Just the way self driven cars are loaded with sensors to make it learn how to drive, Amazon Go stores use cameras to track a user’s action in the store. The amazon Go stores use a system of cameras, sensors and/or RFID readers to identify shoppers and the items they’ve chosen. Signals and data from all these sensors are fed computers to identify customer interactions.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Amazon-Go/blob/main/images/img5.png" />

For example, if computer vision detects that a customer is going to place or pick an item, then it will trigger the smart shelfs with weight and RFID sensors to find whether customer is picking an item or placing back an item.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Amazon-Go/blob/main/images/img6.png" />

# 3. Deep Learning - YOLO

---

YOLO or You Only Look Once is a convolution neural network that can locate and classify objects in a picture. Before YOLO there were other convolution networks that can perform the same task, but they were extremely slow. Thus they can't be used on cars with autopilot. Also, earlier networks first locate the object, then classify it. But YOLO as the name suggests an image is used only once to locate and classify it.

The following picture shows yolo architecture.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Amazon-Go/blob/main/images/img7.png" />

Amazon Go stores use YOLO to locate, and track humans in a store. After locating human in frames, the frames is fed to another computer vision algorithm that will estimate pose of human and find whether human is picking or walking in the store. 


