📄 TASK 6: Host a Static Website with GitHub Pages
________________________________________
Step 1: Clone the Repository and Create index.html
1.	Clone your GitHub repository (skip if already clone)
                 git clone https://github.com/ramakrishna-k7/task-6
                 cd task-6
2.	Create the index.html file:
              touch index.html
3.	Edit index.html
Add the following content: 
    Index.Htm
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>My Webpage</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background: #f9f9f9;
            color: #333;
            padding-bottom: 80px; /* space for footer */
        }

        header {
            background: linear-gradient(135deg, #007BFF, #0056b3);
            color: white;
            padding: 2rem 1rem;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
            animation: fadeInDown 1s ease-in-out;
        }

        main {
            max-width: 960px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        h2 {
            margin-top: 2rem;
            color: #007BFF;
            border-left: 5px solid #007BFF;
            padding-left: 0.5rem;
        }

        p, li {
            margin: 1rem 0;
            font-size: 1.1rem;
        }

        ul {
            padding-left: 1.5rem;
        }

        ul li {
            padding: 0.5rem 0;
            transition: transform 0.2s;
        }

        ul li:hover {
            transform: translateX(5px);
            color: #0056b3;
        }

        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
            font-size: 0.9rem;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <main>
        <h2>About Me</h2>
        <p>Hello! my name is ramakrishna, I'm learning how to create and host websites using GitHub Pages. This is a basic static site using HTML and CSS.</p>

        <h2>Projects</h2>
        <ul>
            <li>Personal Portfolio</li>
            <li>devops engineer</li>
            <li>Aws devops</li>
        </ul>
    </main>

    <footer>
        &copy; 2025 My Webpage. All rights reserved.
    </footer>
</body>
</html>



4.	Stage and commit the file:
          git add index.html
          git commit -m "first commit"
5.	Push to GitHub:
        git push -u origin main
________________________________________
✅ Step 2: Enable GitHub Pages
1.	Go to your repository on GitHub.
2.	Click on Settings (gear icon).
3.	Scroll down to Pages section.
4.	Under "Source", select the main branch and root (/) folder.
5.	Click Save.
6.	GitHub will generate a URL like:
   
Website_link:
https://ramakrishna-k7.github.io/Task-6/







