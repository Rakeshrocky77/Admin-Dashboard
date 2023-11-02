# Admin-Dashboard
 {
    padding: 0px;
    margin: 0px;
}

.main {
    display: flex;
    flex-direction: row;
    width: 100vh;
}

.left {
    background-color: rgba(241, 233, 233, 0.267);
    width: 500px;
    height: 650px;
}

img {
    width: 25px;
    height: 25px;
}
.right {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
}

.leftone, .rightone {
   display: flex;
   flex-direction: column;
   justify-content: center;
}

.second {
    background-color: rgb(245, 245, 141);
}

.section1 {
    background-color: rgb(238, 162, 162);
    width: 1000px;    
}

.searchbar {
    padding-top: 10px;
    text-align: center;
}

input {
     width:500px;
     border-radius: 20px;
}

button {
    background: red;
    color: white;
    border-radius: 10px;
}

/*.pins, .pins1, .pins2, .pins3 {
   background: blue;
   color: white;
   border: 1px 2px 1px 2px solid blue;
   border-radius: 8px;
   display: center;
   justify-content: end;
}*/
.section2 {
    display: flex;
    flex-direction: row;
    width: 500px;
}

.container {
    display: grid;
    grid-template-columns: 200px 200px;
    grid-template-rows: 200px 200px;
    grid-auto-columns: 200px;
    gap: 10px;
}

.items {
    background-color: lightblue;
    border: 1px sold red;
}

.boxes {
    border: 2px solid green;
}

.square {
    border: 3px solid red;
}