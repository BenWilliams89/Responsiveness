# Responsive Nav Bar

body {
    font-family: 'Open Sans', sans-serif;
}

h1 {
    font-size: 6em;
    text-align: center;
    color: red;
}
nav {
    font-size: 1.5em;
    display: flex;
    justify-content: space-between; /* This seperates the 3 different links */
}



ul,li {
    display: inline;
    margin: 0;
    padding: 0;
}

ul {
    flex: 1;
    max-width: 50%;
    display: flex;
    justify-content: space-evenly;
}


@media (max-width: 768px){
    h1 {
        font-size: 4em;
    }
    nav, nav ul {
        flex-direction: column;
        align-items: center;   
    }
    
}

@media (max-width: 576px){
    h1 {
        font-size: 3em;
    }
}


@media (min-width: 400px) {
    h1 {
        color: rgb(180, 116, 7);
    }
}

@media (min-width: 1000px) {
    h1 {
        color: rgb(11, 123, 62);
    }
}

@media (min-width: 1200px) {
    h1 {
        color: rgb(27, 41, 198);
    }
}