Apktool v2.4.1 Released

This release continues patches for both aapt1/aapt2, 
with regards of ensuring a static binary to fix issues 
on Windows. This is probably one of the last releases 
where aapt2 is opt-in, instead of being the default. 
Another great fix included in this release is fixing 
issues related to the non-stop problem of recording the 
compression type of included files. Now files are written 
to a temporary file and that file is passed onward to aapt. 
Thanks to peret for taking lead and fixing all of that up.

As a final note, I've moved the building of aapt1/aapt2 binaries 
to AOSP master branch, as using official tags were lacking patches 
that were required. I can't wait on the release cycle of tools and 
Android 11, so we've swapped to master.

Continuing from the last release, the community stepped in massively
 to help deliver pull request after pull request for changes. I'm very 
 thankful for anyone who decides to help and contribute to the project.

This release had 90 commits by 11 people.

+Connor Tumbleson (iBotPeaches) - 72 commits

+Igor Eisberg - 4 commits

+Adib Faramarzi (adibfara) - 2 commits

+Daniel Malmqvist - 2 commits

+Frieder Bluemle (friederbluemle) - 2 commits

+Peter Retzlaff (peret) - 2 commits

+huangweijie - 2 commits

+Brian Pak (brianairb) - 1 commit

+Shaheen Gandhi - 1 commit

+Bruno Passeri (Varstahl) - 1 commit

+yangjing.yeoh (JingYeoh) - 1 commit

Check out other version of apktool: https://ibotpeaches.github.io/Apktool/
