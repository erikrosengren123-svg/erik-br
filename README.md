#wrapper{
width: 100%;
    min-height: 95vh;
    border: 1px solid;
    margin: auto;

    display: grid;

    grid-template-areas:
        "hd hd"
        "nv nv"
        "c1 c2"
        "c3 c3"
        "f1 f2";

    grid-template-columns: 1fr 1fr;
    grid-template-rows: 120px auto 200px 200px 100px;

}

#hd{
    background-color: rgb(247, 229, 212);
    grid-area: hd;
    text-align: center;
    align-content: center;
}

#nv {
    background-color: rgb(247, 229, 212);
    grid-area: nv;
}

#c1 { grid-area: c1;
    background: rgb(247, 229, 212);
 }

#c2 { grid-area: c2;
     background: rgb(247, 229, 212) ;
    }

#c3 { grid-area: c3; 
    background:rgb(247, 229, 212);
     }



#f1 {
    background-color:rgb(247, 229, 212);
    grid-area: f1;
}

#f2 {
    background-color: rgb(247, 229, 212);
    grid-area: f2;

}