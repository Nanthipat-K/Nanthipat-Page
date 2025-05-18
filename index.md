<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nanthipat Kongborrirak - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f8f8; /* Light gray background */
            color: #333; /* Dark text */
            line-height: 1.6;
        }
        .container {
            max-width: 800px; /* Slightly narrower container for minimal feel */
            margin: 40px auto; /* Add more vertical margin */
            padding: 20px;
            background-color: #fff; /* White background for the content area */
            border-radius: 12px; /* More rounded corners */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Slightly stronger shadow */
        }
        .section {
            margin-bottom: 30px; /* More space between sections */
            padding-bottom: 20px;
            border-bottom: 1px solid #eee; /* Subtle separator */
        }
        .section:last-child {
            border-bottom: none;
        }
        .section-title {
            font-size: 1.6rem; /* Slightly smaller title */
            font-weight: 700;
            margin-bottom: 15px;
            color: #222; /* Darker title color */
        }
        .profile-picture {
            width: 150px; /* Size of the profile picture */
            height: 150px;
            border-radius: 50%; /* Make it round */
            object-fit: cover; /* Ensure the image covers the area */
            margin: 0 auto 20px auto; /* Center and add bottom margin */
            display: block; /* Center the image */
            border: 4px solid #007bff; /* Add a border */
        }
        .experience-item {
            margin-bottom: 15px; /* Less space between experience items */
        }
        .experience-title {
            font-size: 1.1rem; /* Slightly smaller experience title */
            font-weight: 600;
            margin-bottom: 3px;
        }
        .experience-date {
            font-size: 0.85rem; /* Smaller date font */
            color: #666;
            margin-bottom: 8px;
        }
        .skill-list {
            list-style: none; /* Remove default list style */
            padding: 0;
            display: flex; /* Use flexbox for skills */
            flex-wrap: wrap; /* Wrap skills to the next line */
            gap: 10px; /* Space between skill items */
        }
        .skill-item {
            background-color: #e9e9eb; /* Light background for skill tags */
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.9rem;
        }
         .link-button {
             display: inline-block;
             background-color: #007bff; /* Blue button */
             color: white;
             padding: 8px 15px;
             margin-top: 10px;
             border-radius: 5px;
             text-decoration: none;
             transition: background-color 0.3s ease;
             font-size: 0.9rem; /* Smaller button font */
        }
        .link-button:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
    </style>
</head>
<body>

    <div class="container">

        <section class="text-center section">
            <img src="placeholder.jpg" alt="Your Profile Picture" class="profile-picture">
            <h1 class="text-3xl font-bold text-gray-800 mb-1">Nanthipat Kongborrirak</h1>
            <p class="text-lg text-gray-600">Language and Technology Student</p>
        </section>

        <section class="section">
            <h2 class="section-title">About Me & Skills</h2>
            <p class="mb-6">
                Language and Technology student with a focus on Natural Language
                Processing and linguistics. Skilled in data acquisition, data analysis, and
                developing/evaluating NLP models. Successfully applied skills in
                projects involving sentiment transfer and comprehensive LLM
                performance assessment in Thai. Passionate about building innovative
                language technologies and ready to contribute to cutting-edge projects.
            </p>
            <h3 class="text-lg font-semibold mb-3">Skills:</h3>
            <ul class="skill-list">
                <li class="skill-item">Python, HTML, and SQL</li>
                <li class="skill-item">Machine Learning</li>
                <li class="skill-item">LLMs and Prompt Engineering</li>
                <li class="skill-item">Natural Language Processing</li>
                <li class="skill-item">Linguistics</li>
                <li class="skill-item">Interpersonal/Communication skills</li>
            </ul>
        </section>

        <section class="section">
            <h2 class="section-title">Experience</h2>

            <div class="experience-item">
                <h3 class="experience-title">NLP Group Project</h3>
                <p class="experience-date">November 2023 – December 2023</p>
                <ul class="list-disc ml-5 text-gray-700 text-sm">
                    <li>Performed a 'neutral reframing' sentiment transfer task, converting negative Thai text to neutral.</li>
                    <li>Led dataset creation and annotation for Thai text sourced from free and social media platforms.</li>
                    <li>Fine-tuned multi-lingual models (mBart, mT5) pre-trained on Thai data using the mentioned dataset.</li>
                    <li>Applied augmentation via English-to-Thai translation to increase the size of dataset.</li>
                </ul>
                <p class="mt-3">
                    <a href="#" class="link-button">More Detail (Placeholder)</a>
                    </p>
            </div>

            <div class="experience-item">
                <h3 class="experience-title">Research Assistant at Motohashi Lab</h3>
                <p class="experience-date">May 2024 – July 2024</p>
                <ul class="list-disc ml-5 text-gray-700 text-sm">
                    <li>Developed a system to extract and analyze patent and product information through web crawling.</li>
                    <li>Applied topic modeling techniques to identify key themes within the data.</li>
                    <li>Implemented a dual attention model to enhance the relationship mapping between textual data from patents and products.</li>
                    <li>Developed a recommendation system leveraging the insights from the dual attention model to suggest relevant products based on a given patent or vice versa.</li>
                </ul>
                <p class="mt-3">
                    <a href="https://github.com/Nanthipat-K/github-pages/blob/e0b103ed4e898f2012628c475f55bfbf4b91d7e5/pdf/Text%20mining%20by%20using%20Python2024%20Report.pdf" class="link-button">More Detail</a>
                    </p>
            </div>

            <div class="experience-item">
                <h3 class="experience-title">Senior Project</h3>
                <p class="experience-date">January 2025 – April 2025</p>
                <ul class="list-disc ml-5 text-gray-700 text-sm">
                    <li>Evaluated the reading and comprehension proficiency of various Large Language Models (LLMs) in the Thai language, utilizing OpenRouter Al for API access to models and DSPy for experimenting different prompting strategies.</li>
                    <li>Benchmarked multilingual (GPT-40, Gemini Flash 2.0, DeepSeek V3) and Thai fine-tuned models (Typhoon2 8B, 70B) using Thai national exam datasets (A-Level, CU-TPT, O-NET).</li>
                    <li>Found that larger models achieved higher accuracy and few-shot prompting improved the performance especially smaller models. LLMs exceeded human average on less complex questions.</li>
                </ul>
                 <p class="mt-3">
                    <a href="https://github.com/Nanthipat-K/github-pages/blob/e0b103ed4e898f2012628c475f55bfbf4b91d7e5/pdf/Assessment%20of%20a%20Large%20Language%20Model%E2%80%99s%20Reading%20and%20Comprehension%20Proficiency%20in%20the%20Thai%20Language.pdf" class="link-button">More Detail</a>
                    </p>
            </div>

        </section>

        <section class="section">
            <h2 class="section-title">Contact</h2>
            <p class="text-gray-700"><strong>Phone:</strong> 083-771-9567</p>
            <p class="text-gray-700"><strong>Email:</strong> nanthipat.ko@gmail.com</p>
            </section>

    </div>

</body>
</html>
