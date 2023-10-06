## ipatool for iOS
This is a port of Majd Alfhaily's [ipatool](https://github.com/majd/ipatool) adapted to run on iOS

### Build / Installation
To build this, make sure you have AppSync installed on your iOS device, and then simply build the "ipatool" scheme (don't bother to change any of the signing capabilities)

If the build was successful, the app will launch and immediately crash, you can also confirm this by watching xcode's console below as there is a test arguement set. Once built, navigate to the app's bundle directory and copy the 'ipatool' executable to /usr/local/bin, at this point you can feel free to delete the app.

If you rather just install without building, I've added a pre-compiled .deb to the releases, and you can then read the documentation provided on Majd's repo for a full list of usages

### Credits
Obviously Majd Alfhaily for providing such an awesome [tool](https://github.com/majd/ipatool) and a special thank-you to John Coates for providing [flexdecrypt](https://github.com/JohnCoates/flexdecryptl) which this projects file hierarchy is heavily based on

[My Mastadon](https://mastodon.social/@dlevi)  

## Troubleshooting
As of today’s date (October 5th, 2023) this is *still* working. If you do happen to have any problems with 2FA, please refer to this [thread](https://github.com/dlevi309/ipatool-ios/issues/2#issuecomment-1078571991) 

If this ever breaks, I’ll push out an update, but at this point it seems unlikely.