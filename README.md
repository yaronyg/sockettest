# sockettest
A quick and dirty test for some socket code

All the express/jade/etc. code can be ignored. That was just created when I created a new Node.js project in Intellij
and I didn't bother to remove it. The key file is sockettest.js. That is the file that I copy over to 
Thali_CordovaPlugin.

I have run this exact project with Node v0.12, Node v0.10 and JX v0.10.38 (at least that is what it says when I
ask for its version). It passed in all environments. So I'm trying to figure out then why this code won't pass
when we run it on Android.

To run this test just clone the repro, run npm install and then run app.js.
