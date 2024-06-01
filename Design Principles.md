# Design Principles for untitledOS
# 1. Toolbars are an annoyance
Toolbars (e.g. File | Edit | View | Help) are annoying. These impede the user experience as they don't allow quick 1-click access to common actions. They hide away actions and it is much better to organise actions in a more readily available way if possible.

# 2. Applications should be reasonably self-contained
For example in a text editor, the user shouldn't have to open up their file manager to delete the text file they're currently looking at. They should be able to perform this action from inside the text editor. This principle is extremely important to the user feeling that the user is working for them and not against them.

Having to switch back and forth between applications is frustrating when the user is only carrying out a single workflow, for example text or image editing. Text editing should be able to all be done from within the text editor, including management of text files in some sense - like deleting or creating them - and the file manager shouldn't be relied on for simple actions such as these.

# 3. The GUI should be fully featured
This sounds obvious, but so many systems either don't care or don't manage to achieve this to a high level of success. A system designed for use with a GUI should be able to be used and configured entirely in GUI.

A great example of a system which does this reasonably well is Microsoft Windows. Windows has GUI for pretty much anything you could think of to do on Windows. On Windows, a user could easily use it for decades and get everything they need from it without ever having to touch the terrifying black void of the command prompt. Windows has an absolute mess of a GUI because of its complex history and commitment to backwards compatability, but it is still a good example.

# 4. Common Application functions should be consistent across all programs
Common functions in applications should be similar across the system. If a user is proficient in using a text editor then they should know how to copy and paste in an image editor, an IDE and even a video editor. This can be difficult to get right, but it is important as it speeds up the user's interfacing with the system and allows for the user to easily learn the system through a collection of basic concepts rather than through learning one huge application at a time, especially if someone is new to using desktop computers.

# 5. Control should be given to the user.
The user should feel like they have full control over the system at all times. When a user loses control over the system due to a freeze or crash, it becomes very frustrating, very fast. The user shouldn't feel like the system is trying to pamper them and do everything for them, but equally the system should perform tasks that the user would feel are obvious for the system to do for them.

Microsoft Windows is infamous for its history of system updates outright taking control from the user. This is a great example because the reason this has become such a meme shows that taking control from the user is extremely frustrating, so it should never be done.

Nagging is also not the correct way to go about taking care of the user. Notifications, espeically incessant ones, can completely disrupt a user's workflow and become very annoying over time. Nags and notifications should be used sparingly, if at all. System notifier icons in the tray are a less offensive way of nagging the user, if it is necessary, as it doesn't cover up valuable screen space that the user is working with. Imagine if someone just came up to your desk and stuck a post-it note on it every few minutes but quickly took it away. Taking it away doesn't make it not annoying. It's still very frustrating.

Rant over. Time to make some awesome software.
