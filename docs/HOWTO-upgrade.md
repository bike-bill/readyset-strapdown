ReadySET: How to upgrade {#readyset-how-to-upgrade}
------------------------

### [Disclaimer](#disclaimer)

ReadySET is still in fairly early releases that are rapidly evolving.
The differences between any two early releases may be quite large,
making upgrading difficult.

As ReadySET matures (i.e., passes v1.0.0), the changes between minor
versions should become smaller and easier to upgrade.

Also, some of the ReadySET content that is most likely to change and
grow over time is not part of the templates at all, it is the [words of
wisdom](http://readyset.tigris.org/words-of-wisdom/) hosted on the
ReadySET web site.

### [Low-Tech Upgrade Proceedure](#low-tech-upgrade-proceedure)

You may simply cut and paste sections of HTML source code between new
ReadySET templates and files that you have been using in your project.

While potentially tedious and somewhat error-prone, this method requires
no training or specific tools. It also has the advantages that it is
very easy to update only as many or as few files as you desire.

Check the release-notes.html in the new release of ReadySET for a
summary of changes.

### [High-Tech Upgrade Proceedure](#high-tech-upgrade-proceedure)

For users that use CVS for their own project: you can use CVS's [vendor
branch](http://cvsbook.red-bean.com/cvsbook.html#Tracking_Third-Party_Sources__Vendor_Branches_)
feature to help you merge the latest changes from the ReadySET project
into your project.

Let's assume that you are upgrading from ReadySET v0.8.2 to v0.9.1.
Let's also assume that you consider "Tigris.org" to be the vendor of
ReadySET. Note that CVS does not allow periods in tag names, and we do
not want ReadySET version numbers to conflict with any version numbers
of your projects, so we will make the names more distinctive and use
underscores instead: ReadySET\_0\_8\_2, ReadySET\_0\_9\_1, Tigris\_org.

Let's further assume that you are using a CVS server located at
cvs.yourcompany.com with a repository located at /cvs, your username is
username, and that you are using ReadySET for a project named
yourproject.

Steps:

1.  Unpack ReadySET v0.8.2 and add it to **your** CVS repository on a
    vendor branch.

          unzip ReadySET-082.zip
          cd ReadySET-082/templates
          cvs -d :pserver:username@cvs.yourcompany.com:/cvs import -m 'importing ReadySET v0.8.2' yourproject Tigris_org ReadySET_0_8_2
          cd ..
          

2.  Unpack ReadySET v0.9.1 and add it to **your** CVS repository on the
    same vendor branch.

          unzip ReadySET-091.zip
          cd ReadySET-091/templates
          cvs -d :pserver:username@cvs.yourcompany.com:/cvs import -m 'importing ReadySET v0.9.1' yourproject Tigris_org ReadySET_0_9_1
          cd ..
          

3.  Create a working copy of your project documents (if you don't
    already have one).

           mkdir workingcopy
           cd workingcopy
           cvs -d :pserver:username@cvs.yourcompany.com:/cvs co yourproject
          

4.  Merge the **differences** between the two vendor versions of
    ReadySET into your working copy.

           cd yourproject
           cvs update -j ReadySET_0_8_2 -j ReadySET_0_9_1
          

5.  You are likely to see several messages from CVS about merging files
    and conflicts. The CVS output lines that begin with "C"
    indicate conflicts.
6.  Edit your working copy files to resolve all conflicts. Browse the
    files to make sure that they look OK. If any files have changed
    names, you will have to cut and paste content from the old filename
    to the new filename.
7.  Commit your updated files to your repository

           cvs commit -m 'updated project documents to use newer ReadySET templates'
          

These steps are specific to CVS, but other version control systems
likely provide analogous functionality.


