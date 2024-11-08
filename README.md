# Welcome!

This is the back-end of my personal website, [**episanty.github.io**](https://episanty.github.io). You can head on over there to see the content, or you can use this repository to see how it is built.

To run this locally, simply run
```bash
jekyll serve
```
on the root directory, and load `http://localhost:4000/`.


This website is based on the [Wall-E Jekyll template](https://github.com/abhn/Wall-E) by Abhishek Nagekar.


To get this running on a new linux machine
 - install jekyll:
```bash
sudo apt-get install jekyll
```
 - install the jekyll-paginate gem:
```bash
gem install jekyll-paginate
```
To get this running on a new Windows machine
 - install jekyll as per 
   https://jekyllrb.com/docs/installation/windows/
   Thus far, this seems highly fragile and liable to fail -- tried a whole bunch of times and eventually succeeded, with no clear idea of what made it work. Keep a close eye on the PATH variable and on the output of `ridk version`.
 - finally, install the jekyll-paginate gem:
```bash
   $ gem install jekyll-paginate
```
