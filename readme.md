OK, I can see that many people suffer from Photos crash on MacOS, when they have a relatively large library on external drive. I spent a day, and it seems I found solution, that will hopefully help the others. If you experienced Mac crash when Photos tries to upgrade the library and hangs at some 6%, 11% or 66% progress level, then leading to system crash, the lessons I learnt will help you. 

The Bottleneck problem. Use Thunderbolt cable on older Macs, USB-C is fine on new ones. Do not use old USB connection on older Macs. I discovered the Bottleneck while trying simultaneously delete directory via command line and open drive content in Finder. "Resource is busy" and the rainbow ball that you will have. 

Switch off the indexing of your external drive in Spotlight preferences. Switch off iCloud sync for Photos. 

If you have anything constantly monitoring your filesystem for logging files usage (in my case that was Timing app), switch it off and switch off its agent application. 

Restart machine. Open Disk Utility and check your external drive for consistency. If that fails, turn off the machine and re-attach drive with a better cable (Thunderbolt). 

Verify and repair external disk with First Aid option. 

Now (fingers crossed) your Photo app will be able to update library to the end even if it is large. 

If not, or if you have no better cable, you are doomed. The solution will be to find the guy with a better specs Mac and copy the evil library there, update it there and split to smaller chunks by topic, like no more than 20GB each. 

That will be tedious. After that - never use Photos again, switch to Lightroom, since Photos is for casual use as it was discovered, not for keeping the large archive or intensive photography life. 
