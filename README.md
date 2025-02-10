# Computer-Architecture

![image](https://github.com/user-attachments/assets/26d40f90-4b8a-4658-b2c7-dad4f834c472)

![image](https://github.com/user-attachments/assets/06bdca35-17c6-4948-9401-cac3f0f36cf7)

(04-02-2025)-Basics of Computer Architecture

![image](https://github.com/user-attachments/assets/5e99ea13-e703-4f64-8bd0-da170833b6c2)

When we need to perform an operation, there are multiple ways to do, and a particular way is selected to perform the operation.

![image](https://github.com/user-attachments/assets/a9b1cfac-f48d-4965-bc27-740bac1367b6)

![image](https://github.com/user-attachments/assets/8232a0c2-b016-4c01-b4ac-4c753828e1c2)

![image](https://github.com/user-attachments/assets/07783c6d-7968-4e2f-a10b-6ee385b4c25b)

Classifications of Computer Architecture

In Von Neuman Architecture, both the data and instructions are stored in the same memory and travel through the same path. So, the processor cannot simultaneously read instruction and operate on data. This is known as Von-Neuman Bottleneck.

![image](https://github.com/user-attachments/assets/edef6333-4242-4da3-b402-53ada374e657)

Coming to the Harvard Architecture, two different memory are present for instruction and data. So, the computer under this category will be faster. In Modified harvard Architecture, a cache memory will be present and this is used in modern computers. 

![image](https://github.com/user-attachments/assets/f7fe42d9-8f29-454c-8eea-44ffc87a1da3)

Von-Neuman architecture comes under SISD. Here, Control->CPU

![image](https://github.com/user-attachments/assets/4e894d4f-3ce8-4b74-95ac-a5c894bff163)

Introduction to Memory

![image](https://github.com/user-attachments/assets/1e965e9d-0523-4436-87a1-2068ca13ee31)

The data which are stored for immediate access are stored in primary memory and for permanent storage, we use secondary memory. Let us say that we need play an audio file. So, the system manager will manages the space in the primary storage and get the data from the secondary storage and use the default application to play the file.

![image](https://github.com/user-attachments/assets/6d894b0c-a0a7-4b96-9da4-0dd239f03dad)

As we need to perform the operation as quick as possible, we can access the data from the primary memory in any order. And so it is called as RAM. And Dynamic RAM which has a transistor and capacitor is used mostly.

![image](https://github.com/user-attachments/assets/9c5cc77e-767b-4e5d-9c50-6a84ebdf65ed)

And for the further fast primary storage, we use cache. And all these primary memory storage elements are volatile, which means that the data will be stored there only till the power is ON. Also, these are costlier than the secondary memory.

![image](https://github.com/user-attachments/assets/5e3fe996-3d3f-4f5a-8b1a-303d61b13128)

![image](https://github.com/user-attachments/assets/1630470b-6cef-4a95-9325-e3e457b311d1)

The cache and main memory will communicate with each other by using 'blocks or words' and this data communication is called, cache memory mapping. But, these memories will not retain data permanently. So, we need secondary storage. Having the single large storage is not the good solution. We should have storage elements as shown below, for faster computing.

![image](https://github.com/user-attachments/assets/35efbe1f-44dd-43c1-85a0-b94c90f9a567)

Memory Hierarchy & Interfacing

![image](https://github.com/user-attachments/assets/6fd945ea-8d40-43b5-90a6-784546df5849)

