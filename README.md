# css-code

.header{
    display: flex;
    flex-direction: row;
    height: 150px;
    justify-content: space-between;
    /* background-color: beige; */
    margin-top: 10px;
}
.logo-img{
    height:180px;
    /* width:200px; */
}

.right-section{
    display: flex;
    flex-direction: row;
    width: 450px;
    margin-right: 20px;
    flex-shrink: 0;
    justify-content: space-between;
    padding-bottom: 40px;
}
.icon-image{
    height: 160px;
    margin-top: 0;
    margin-left: 0;   
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

nav {
    /* background-color: white; */
    padding: 10px;
}

.nav-links {
    list-style: none;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.nav-links li {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.nav-links a {
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    text-decoration: none;
    color: #333;
    font-size: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;

}

.nav-links img {
    width: 80px;
    height: 80px;
    margin-top:12px;
    margin-bottom: 5px;
    margin-left: 10px;
    display: flex;
    justify-content:space-around;
    /* flex-direction: row; */
    column-gap: 5px;
}

.nav-links a:hover {
    color: #ff6347;
}






