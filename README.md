Invictrix
====================

Getting Started
---------------
To get started with building Invictrix, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

Initialize Source
--------------------
(Assuming you have a valid build environment setup)
- mkdir invictrix (or whatever you want to name the source folder)
- cd ~/invictrix
- repo init -u https://github.com/InvictrixROM/manifest.git -b o-mr1

Sync Source
--------------------
- repo sync -c -f -jx --force-sync --no-clone-bundle --no-tags (x being however many cpu jobs, you can also use -c to sync only the current branch specified by repo init)

Build Source
--------------------
- . build/envsetup.sh

Choose Device
--------------------
- lunch invictrix_*device*-userdebug

Clean Builds
--------------------
- cd ~/invictrix
- repo sync -c -f -jx --force-sync --no-clone-bundle --no-tags (x being however many cpu jobs, may also use -c as above)
- lunch and pick the right device (refer to above for choosing right device to build)
- make clean
- make bacon -j# (# being however many cpu jobs, for example i build with -j13)

DMCA Copyright Infringement Notification
--------------------
Official DMCA Copyright Infringement Notification

Our ROM builds follow the safe harbor provisions of 17 U.S.C. §512, otherwise known as Digital Millennium Copyright Act (“DMCA”).

To file a copyright infringement notification with us, you will need to send a written communication that includes substantially the following:

- A physical or electronic signature of a person authorized to act on behalf of the owner of an exclusive right that is allegedly infringed.
- Identification of the copyrighted work claimed to have been infringed, or, if multiple copyrighted works at a single online site are covered by a single notification, a representative list of such works at that site.
- Identification of the material that is claimed to be infringing or to be the subject of infringing activity and that is to be removed or access to which is to be disabled, and information reasonably sufficient to permit the service provider to locate the material. Providing URLs in the body of an email is the best way to help us locate content quickly.
- Information reasonably sufficient to permit the service provider to contact the complaining party, such as an address, telephone number, and, if available, an electronic mail address at which the complaining party may be contacted.
- A statement that the complaining party has a good faith belief that use of the material in the manner complained of is not authorized by the copyright owner, its agent, or the law.
- A statement that the information in the notification is accurate, and under penalty of perjury, that the complaining party is authorized to act on behalf of the owner of an exclusive right that is allegedly infringed (Note that under Section 512(f) any person who knowingly and materially misrepresents that material or activity is infringing may be subject to liability for damages. In other words, DON’T MAKE FALSE CLAIMS!

To expedite our ability to process your request, such written notice should be sent to our designated agent whose contact information is available via our “DMCA Designated Agent” listed below:

- Jacob McSwain
- 405-517-1253
- jacob.a.mcswain@gmail.com

Credits
--------------------
- Google for AOSP
- Lineage OS
- Dirty Unicorns
- Carbon ROM
- gagan3421 for bootanimations
- beanstown106
- Others we may have missed
