Testing

Test 1: I tried to click the update button yet the display line was not appearing. It turns out that there was a missing backtick within
the update inputs elements. Thus the display line was not being created properly. I added the backtick and the panel was shown.

Test 2: After adding the new values, upon clicking the save button, the updates were not being saved. I verified this by clicking the view button on
the selected animal. I used a console.log to check which animal object was being accessed. It turns out I forgot to specify the index parameter. This
meant that an invalid object was being accessed. I added in the [index] and the updated began to show.

Test 3: Lastly, the click buttons were not appearing after I saved the changed. This was due to the target handle function not being included
in the end. Once I copied the code over from the create function, the click handlers began working properly.
