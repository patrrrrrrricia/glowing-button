# GlowingButton

<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buton Roz Pudrat</title>
    <style>
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #121212; 
        }

        .glowing-btn {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            padding: 14px 28px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 15px;
            font-weight: 600;
            letter-spacing: 1px;
            text-decoration: none;
            color: #ffffff;
            background: linear-gradient(135deg, #d4a5b8, #b87d95);
            border: none;
            border-radius: 50px;
            box-shadow: 0 4px 15px rgba(184, 125, 149, 0.3),
                        0 0 20px rgba(212, 165, 184, 0.2);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .glowing-btn:hover {
            transform: translateY(-2px);
            background: linear-gradient(135deg, #e0b4c7, #c489a2);
            box-shadow: 0 6px 25px rgba(212, 165, 184, 0.5),
                        0 0 35px rgba(212, 165, 184, 0.4);
        }

        .glowing-btn:active {
            transform: translateY(1px);
        }

        .glowing-btn svg {
            width: 18px;
            height: 18px;
            fill: currentColor;
        }
    </style>
</head>
<body>

    <div class="container">
        <a href="https://patrrrrrrricia.github.io/glowing-button/" class="glowing-btn" target="_blank">
            <svg viewBox="0 0 24 24">
                <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/>
            </svg>
            GLOWING BUTTON
        </a>
    </div>

</body>
</html>

---

## Overview
A fusion of soft neon aesthetics and clean frontend code. **GlowingButton** serves as the immersive entry point to my portfolio, reimagining standard UI through an aesthetic lens.

---

## Tech Stack
* **Architecture:** HTML5 & CSS3
* **Styling:** Multi-layered Box-Shadow Stacking & Neon Algorithms
* **Experience:** Interactive Hover & Pulse Animations

![HTML5](https://img.shields.io/badge/HTML5-%23333333.svg?style=for-the-badge&logo=html5&logoColor=%23FF69B4) ![CSS3](https://img.shields.io/badge/CSS3-%23333333.svg?style=for-the-badge&logo=css3&logoColor=%23FF69B4) ![Design](https://img.shields.io/badge/Design-Digital_Couture-%23FF69B4.svg?style=for-the-badge)

---

## Core Functionality
* **Luminescence Engine:** Realistic light bleed effect using CSS variable layering and perspective transforms.
* **Flicker Logic:** Custom `@keyframes` (border, text, and faulty-letter) simulating vintage neon tube physics.
* **Sartorial Interaction:** Smooth transitions and blur filters that activate upon user engagement.

  

https://github.com/user-attachments/assets/fc5b0d7d-2d45-4eec-b3e4-0c722f0aaaec



---

## Project Structure
* **`index.html`**: The structural backbone of the signature.
* **`style.css`**: The "Couture" layer containing the neon algorithms.
* **`photo/`**: Visual documentation of the glow.

---


© 2024 Glowing Button | Developed by [**𝐋𝐞𝐨𝐧𝐭𝐞 𝐏𝐚𝐭𝐫𝐢𝐜𝐢𝐚-𝐌𝐢𝐫𝐚𝐛𝐞𝐥𝐚**](https://patrrrrrrricia.github.io/glowing-button/)


