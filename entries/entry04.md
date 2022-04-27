# Entry 4
##### 3/23/22

### Learning | What is Xcode?
During this past time, I have been learning a lot about the Xcode interface. Xcode is an IDE developed by Apple for making software for macOS, iOS, watchOS, and tvOS. It is the only officially-supported tool for creating and publishing apps to Apple’s app store. Xcode itself has a lot of tools built in to support the creation of software. Xcode contains a text editor, a compiler, and a build system. Xcode itself also supports a variety of languages. Another neat feature of Xcode is that it has templates for commonly used snippets of code. Making use of the drag and drop method. 

![image](https://user-images.githubusercontent.com/56265985/165410752-d154eaf7-ca88-4f32-8157-c20cd705fcaf.png)

Xcode makes the devlopment process very streamlined and fast. Another very neat feature that Xcode offerds are Storyboards. A storyboard is a visual representation of the user interface of an iOS application, showing screens of content and the connections between those screens. Storyboard enables you to visualize the connection with your IDE to the controller object, and to manage the transfer of data between view controllers. 

![image](https://user-images.githubusercontent.com/56265985/165412011-6efb8309-9194-4877-b9db-fe2f544d3e5d.png)

 ### Development
 ```
 @IBAction func didTapNewNote() {
     guard let vc = storyboard?.instantiateViewController(identifier: "new") as? EntryViewController else {
       return
     }
 ```
 This code snippet connects to the EntryViewController (Storyboard), linking it to whatever I apply it to. In this context, I linked the func. "didTapNewNote" to an add button. The purpose is for making a new note when the func. is used for switcing the screen to a different ViewController. 
 
 <img width="286" alt="Screen Shot 2022-04-26 at 9 17 42 PM" src="https://user-images.githubusercontent.com/56265985/165420838-7905343c-eb1c-4098-a666-66582ee81a4f.png">

Looking at the "Recieved Action" tab you see the "didTapNewNote" linked to a "add" button. I will be using similar code throughout my project to connect various functions. 

### EDP 

I am currently between stage 2 or 3 of the engineering designing process. Learning information and implenting my new found knowlegde into a soulution. Thought to focus I am more leaning to stage 2 as even though I am coding, I am still learning a lot regarding utilizing Xcode and the Swift language. There is still a lot more room for growing. 

### Skills 

#### Time Management 
With college admissions and school, I have a lot on my plate, definitely more than I am used to. 
Because of that Time Management has become very important between balancing my FP and outside school priorities. 

#### Agency 
Due to the nature of the FP using my own agency to find ways to learn how to use Swift and Xcode are prevalent. Google and Youtube have been great resources as well as the Apple Swift documentation.  
 

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
