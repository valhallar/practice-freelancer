# practice-freelancer

**What is this?**  
This repository is a repository for me to recreate [Freelance](https://startbootstrap.com/previews/freelancer) from StartBootstrap.  
It's intend for educational purpose, for me to study how to create HTML and CSS template from looking and console. 

Starting date: June 8th, 2020  
Ending date: June 24th, 2020
Total time: 10 days

**Notes**

1. To change nav's color, add id in section (`<section id="navigation">`). Afterward, us id to select the classes like #navigation a.navbar-brand. 

2. For padding between element inside row, use `<div class="col-sm-12 col-md-6 col-lg-4 px-4 py-4">`

3. Use code below for overlay

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

4. Use `d-flex justify-content-center` to justify row. Case can be found at `<section id="about">`, where there is only two `col-lg-4` (so only 8 part taken, 4 part free), we can used `d-flex justify-content-center` to align `col-lg-4` to center without needing to make new div for the 4 free part.

5. Erase form border with css below: 
```
    border-top: 0;
    border-left: 0;
    border-right: 0;
    border-radius: 0;
    border-color: #e6e6e6;
```

6. To style placehold, use `::placeholder`

7. Used `resize: none;` at textarea for no resize

8. Form sizing using padding css to constrict it down

**Known problem**
1. Overlay can't be in the same size as image
2. Navigation doesn't stick above
