# FileEncryption

As the amount of data in the world has increased exponentially,
data security and protection emerged to be one of the most important
challenges of our time. Nowadays, credit card billings, medical transcriptions or 
invoices etc. are often sent to a person via mail or can be accessed 
using mobile applications. Then this highly sensitive data is stored
unencrypted somewhere on the phones storage.
 
Hence we present **FileEncytpion** - An android application designed to
encrypt data on your android smartphone, safely storing it in a local
database and preventing unauthorized access to your sensitive files.


## How it works

![Contribution guidelines for this project](app/res/images/encryption_concept.png)

TODO INSERT SCREENSHOT WHEN APP IS FINISHED AND PRESENT USE CASE

## Core Blocks

- The application features multiple screen views. 

TODO SCREENSHOT

- The application features a setting screen where a user is able to
configure the language, or select between light mode and dark mode

TODO SCREENSHOT

- The application takes care of permission management by asking the user
for permission of accessing the phones internal storage and furthermore
handles lifecycle management allowing the application to be safely paused
and  terminated as well as used in
portrait mode and landscape mode.

TODO SCREENSHOT

## Feature Blocks

- With [Room](https://developer.android.com/topic/libraries/architecture/room)
this application uses a local database to store and read the encrypted files

TODO SCREENSHOT

- The application enables three different languages using Android resource
 localization a& orientation localization as well as providing different 
 UI layouts for landscape and portrait modes for all views.
 
 TODO SCREENSHOT
 
- FileEncryption uses two APIs
    - [OkHttp](https://square.github.io/okhttp/) - A reliable OpenSource
    HTTP client for HTTP request
    - [krypto](https://github.com/rs3vans/krypto) - A strong, two way 
    encryption wrapper library around the Java Cryptography Architecture 
    (JCA) API, making it easier to use from Kotlin
    
    
# Development Process

- How was work distributed
- How did the initial idea you showed in the preliminary presentation 
change over time.
- Which features would you implement, what would you do differently if 
you were to continue this project with more time?
    
 
 