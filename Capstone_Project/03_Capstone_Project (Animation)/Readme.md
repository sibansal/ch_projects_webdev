# Introduction to Capstone Project - 3
## Made with 💝 for Christel House Students 😊

Clone the content from session 2 and add animation.css to index.html

### Styling
```
#hero h1,h2
{
    animation-name: show;
    animation-duration: 1s;
    animation-timing-function: ease-in;
    animation-fill-mode: forwards;
    opacity: 0;
}

#hero h2
{
    animation-delay: 1s;
}

#hero .btn:hover
{
    border: 3px solid;
    animation: 1s border-animate infinite;
}

@keyframes show
{
    100%
    {
        opacity: 1;
    }
}

@keyframes border-animate {
    0%, 100%
    {
        border-color: aliceblue;
    }
    
    50%
    {
        border-color: chocolate;
    }
}
```