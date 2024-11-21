<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Do You Love Me?</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: whitesmoke;
        }

        h2 {
            text-align: center;
            font-size: 3em;
            color: #e94d58;
            margin: 15px 0;
        }

        .btn-group {
            width: 100%;
            height: 40px;
            display: flex;
            justify-content: center;
            margin-top: 50px;
        }

        button {
            position: relative; /* Changed to relative for proper positioning */
            width: 150px;
            height: inherit;
            color: white;
            font-size: 1.2em;
            border-radius: 30px;
            outline: none;
            cursor: pointer;
            box-shadow: 0 2px 4px gray;
            border: 2px solid #e94d58;
        }

        button:nth-child(1) {
            background: #e94d58;
        }

        button:nth-child(2) {
            background: white;
            color: #e94d58;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <h2 class="question">Do you love me?</h2>
        <img class="gif" alt="gif" src="https://media0.giphy.com/media/t8Lo2mPAzOcmVTgtGe/giphy.gif?cid=6c09b952231uyrnduhdsf4wqnxz03rv9wx3ni5sm0zolrxz3&ep=v1_stickers_related&rid=giphy.gif&ct=s"/>
        <div class="btn-group">
            <button class="yes-btn">Yes</button>
            <button class="no-btn">No</button>
        </div>
    </div>
    <script>
        const wrapper = document.querySelector(".wrapper");
        const question = document.querySelector(".question");
        const gif = document.querySelector(".gif");
        const yesBtn = document.querySelector(".yes-btn");
        const noBtn = document.querySelector(".no-btn");

        yesBtn.addEventListener("click", () => {
            question.innerHTML = "I love you too! 😘";
            gif.src = "https://media1.giphy.com/media/iCVzZwwE6QNAV2tEE0/giphy.gif";
        });

        noBtn.addEventListener("mouseover", () => {
            const noBtnRect = noBtn.getBoundingClientRect();
            const maxX = window.innerWidth - noBtnRect.width;
            const maxY = window.innerHeight - noBtnRect.height;

            const randomX = Math.floor(Math.random() * maxX);
            const randomY = Math.floor(Math.random() * maxY);

            noBtn.style.position = 'absolute'; // Ensure the button can move
            noBtn.style.left = randomX + "px";
            noBtn.style.top = randomY + "px";
        });
    </script>
</body>
</html>
