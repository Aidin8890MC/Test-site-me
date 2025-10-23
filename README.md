# Test-site-me
Test site me
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;700&display=swap">
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rubika mod</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            background: linear-gradient(to bottom, #008EFF, white);
            border: 2px dashed #333;
            padding: 20px;
            position: relative;
          font-family: 'Mikhak', Tahoma, sans-serif;
        }

        /* خط چین دور صفحه */
        body::before {
            content: "";
            position: fixed;
            top: 10px;
            left: 10px;
            right: 10px;
            bottom: 10px;
            border: 2px dashed rgba(0, 0, 0, 0.3);
            pointer-events: none;
            z-index: 1;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            position: relative;
            z-index: 2;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .header h1 {
            color: red;
            font-size: clamp(2rem, 5vw, 3.5rem);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
            margin-bottom: 10px;
        }

        .content {
            background: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .feature-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid limegreen;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #666;
            border-top: 1px dashed #ccc;
        }

        /* رسپانسیو برای موبایل */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .container {
                padding: 10px;
            }
            
            .content {
                padding: 20px;
            }
            
            .features {
                grid-template-columns: 1fr;
            }
            
            body::before {
                top: 5px;
                left: 5px;
                right: 5px;
                bottom: 5px;
            }
        }

        @media (max-width: 480px) {
            .header h1 {
                font-size: 1.8rem;
            }
            
            .content {
                padding: 15px;
            }
        }
      .social-icons {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 30px;
}

.social-icon {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: white;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    transition: all 0.3s ease;
    border: 2px solid limegreen;
}

.social-icon:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

.social-icon img {
    width: 30px;
    height: 30px;
    object-fit: contain;
}

/* برای موبایل */
@media (max-width: 768px) {
    .social-icons {
        gap: 15px;
    }
    
    .social-icon {
        width: 45px;
        height: 45px;
    }
    
    .social-icon img {
        width: 25px;
        height: 25px;
    }
      }
      #ryo  {
        font-family: serif;
      }
      @font-face {
    font-family: 'Mikhak';
    src: url('fonts/Mikhak-Regular.woff2') format('woff2'),
         url('fonts/Mikhak-Regular.woff') format('woff');
    font-weight: normal;
    font-style: normal;
          }
      
   .ot:active  {
     color: black;
     background-color: white;
    background-color: green;
    border: none;
    cursor: none;
    display: flex;
    justify-content: center;
    align-items: center;
     
   }
      .ot {
    padding: 10px;
    width: 324px;
    color: #A3FF7F;
    background-color: #1AE100;
    text-align: center;
    border-color: white;
    font-family: sans-serif;
    font-size: 26px;
    border-style: ridge;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    height: 64px;
    cursor: pointer;
    position: relative;
    border-radius: 32px;
    font-family: "iransans", "B Mitra Bold", mitra, sans-serif;
    font-weight: bold;
    text-decoration: none; /* این خط رو اضافه کردم */
        }

     </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 id="ryo">Rubika patch
            </h1>
            <p></p>
        </div>

        <div class="content">
          
            <p>با روبیکا پچ ، پرمیوم رایگان غیررسمی روبیکا بگیرید.🔥</p>
            
            <div class="features">
                <div class="feature-card ">
✅🔥                  <h2>ایموجی های متفاوت و خاص</h2>
                </div>
                <div class="feature-card">
         🤫🔥           <h2>متن های تغییر یافته</h2>
                </div>
            <div class="feature-card "
                >
          😂😈    <h2>صادق کونیه</h2>
            </div>
        </div>
      <div class="features">
        <a class="ot" href="https://t.me/Rubika_mod_ap_bot">دانلود روبیکا پچ</a>
        <a class="ot" href="./other/about">درباره روبیکا پچ</a>
        <a class="ot" href="./other/texts"> ارسال پیام به پشتیبانی</a>
      </div>
        <div class="footer">
            <p>©   روبیکا پچ ،حقوق محفوظ است</p>
          <p>
  وبسایت  ساخته شده توسط : Sadegh786MC
            <br> کص: <br>Aidin8890MC
          </p>
          <div class="social-icons">
    <a href="https://
          </div>
        </div>
    </div>
</body>
</html>
