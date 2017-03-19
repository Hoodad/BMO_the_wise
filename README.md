BMO your smart friend!
----------------------

This an exstension of the work initially posted here https://learn.adafruit.com/3d-printed-led-animation-bmo
With the additional feature that you can now **ask your BMO** questions!
![BMO animated](https://gifyu.com/images/bmo_saved.gif)

How it works
------------
```flow
st=>start: Start your BMO:>http://adventuretime.wikia.com/wiki/BMO[blank]
e=>end: Turn off your BMO
op1=>operation: Ask a question:>http://en.wikipedia.org/wiki/Question[blank]
cond=>condition: Are all your questions answered?:>http://en.wikipedia.org/wiki/Phrases_from_The_Hitchhiker%27s_Guide_to_the_Galaxy#Answer_to_the_Ultimate_Question_of_Life.2C_the_Universe.2C_and_Everything_.2842.29
io=>inputoutput: Enjoy your BMO

st->op1->cond
cond(yes)->io->e
cond(no)->op1
```

![enter image description here](https://licensebuttons.net/l/by-sa/3.0/88x31.png)
This is uploaded under Creative Commons Attribution-ShareAlike 4.0 International (CC-BY-SA-4.0) license from blog.creativecommons.org

This license lets others remix, tweak, and build upon your work even for commercial purposes, as long as they credit you and license their new creations under the identical terms. This license is often compared to “copyleft” free and open source software licenses. All new works based on yours will carry the same license, so any derivatives will also allow commercial use. This is the license used by Wikipedia, and is recommended for materials that would benefit from incorporating content from Wikipedia and similarly licensed projects