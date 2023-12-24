body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            display: grid;
            grid-template-rows: auto 1fr auto;
            min-height: 100vh;
        }

        header {
            background-color: rebeccapurple;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 15px;
            font-weight: bold;
        }

        section {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(180px,250px));
        }

        #breakfast {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(180px,290px));
        }

        #lunch {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(180px,290px));
        }

        #dinner {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(180px,290px));
        }

        #snacks {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(180px,290px));
        }

        #juice {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(180px,290px));
        }

        @media (max-width:768px) {
        }
        .recipe {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .recipe img {
            max-width: 200px;
            margin-right: 20px;
        }

        .recipe-content {
            flex-direction: column;
            flex: 1;
        }

        .recipe h3 {
            color: rebeccapurple;
               margin-bottom: 10px;
        }

        #search-container {
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 10px;
        }

        #search-input {
         padding: 10px;
        width: 300px;
        font-size: 16px;
        border: none;
        border-radius: 5px 0 0 5px;
        }

        #search-button {
        padding: 10px;
        font-size: 16px;
        background-color: rebeccapurple;
        color: #fff;
        border: none;
        border-radius: 0 5px 5px 0;
        cursor: pointer;
        }

