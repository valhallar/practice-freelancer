# practice-freelancer

**What is this?**  
This repository is a repository for me to recreate [Freelance](https://startbootstrap.com/previews/freelancer) from StartBootstrap.  
It's intend for educational purpose, for me to study how to create HTML and CSS template from looking and console. 

Starting date: June 6th, 2020
Period: 
Ending date: 

**Notes**

1. To change nav's color, add id in section (<section id="navigation">). Afterward, us id to select the classes like #navigation a.navbar-brand. 

2. Use code below for overlay

```
#portfolio .col-sm-12:hover .overlay {
    opacity: 90%;
  }

#portfolio .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    opacity: 0;
    transition: .5s ease;
    background-color: #1abc9c;
    border-radius: 10px;
}

#portfolio .text {
    color: white;
    font-size: 5em;
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    text-align: center;
  }
```

**Known problem**
1. Overlay can't be in the same size as image
