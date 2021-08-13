## Structure of Android Program
- Each app is divided into activities
- The components of Android are
    1. **Activity** - Anything visible to user and responsive
    2. **Broadcast Reciever**/Sender - It waits for a certain Event to create or trigger something(15% or lower battery-> Lock my phone)
        -There can be multiple Broadcast reciever
    3. **Notification** - It shows our message on Notification Bar 
    4. **Service**(Background) - Background programs which always runs even if an app is closed.(Independent - Requires more logic and memory)

## Structure of Android Project
1. activity_main.xml  -> UI/FrontEnd
2. MainActivity.kt    -> Backend
3. manifest.xml       -> Head(Controller) of Project
                        it Contains all settings
4. Resources(Folder)[R]