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
            padding: 30px;
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
            font-weight: 600;
            margin-bottom: 15px;
            color: #222; /* Darker title color */
        }
        .profile-picture {
            width: 150px; /* Size of the profile picture */
            height: 150px;
            border-radius: 50%; /* Make it round */
            object-fit: cover; /* Ensure the image covers the area */
            display: block; /* Center the image */
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
             background-color: #e9e9eb; /* Blue button 007bff */
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

        <section class="section flex items-center"> <img src="pdf/me.jpg" alt="Your Profile Picture" class="profile-picture mr-8"> <div> <h1 class="text-3xl font-bold text-gray-800 mb-1">Nanthipat Kongborrirak</h1>
                <p class="text-lg text-gray-600 mb-4">Language and Information Technologies student Chulalongkorn University</p>
                <div class="contact-info-header"> <p><strong>Phone:</strong> 083-771-9567</p>
                    <p><strong>Email:</strong> nanthipat.ko@gmail.com</p>
                    </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">About Me</h2>
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
                <li class="skill-item">LLMs and Machine Learning</li>
                <li class="skill-item">Natural Language Processing</li>
                <li class="skill-item">Linguistics</li>
                <li class="skill-item">Research</li>
                <li class="skill-item">Interpersonal/Communication skills</li>
                <li class="skill-item">Thai (Native)</li>
                <li class="skill-item">English (TOEIC: 930)</li>
                <li class="skill-item">French (A1)</li>
            </ul>
        </section>

        <section class="section">
            <h2 class="section-title">Experience</h2>

            <div class="experience-item">
                <h3 class="experience-title">NLP Group Project</h3>
                <p class="experience-date">November 2023 – December 2023</p>
                <ul class="list-disc ml-5 text-gray-700 text-sm">
                    <li>Performed a 'neutral reframing' sentiment transfer task, converting negative Thai text to neutral.</li>
                    <li>Led the creation of a custom dataset of 1008 Thai text samples sourced from the Wisesight corpus and the Thai toxic tweet dataset.</li>
                    <li>Fine-tuned multi-lingual models (mBart, mT5) on the dataset, achieving competitive results in automatic and human evaluations.</li>
                    <li>Investigated English-to-Thai translation augmentation, finding that it did not yield significant performance improvements for this task.</li>
                </ul>
                <p class="mt-3">
                    <a href="pdf/NeuThai reframing A Thai language neutral reframing dataset and model.pdf" class="link-button">More Detail</a>
                    </p>
            </div>

            <div class="experience-item">
                <h3 class="experience-title">Research Assistant at Motohashi Lab</h3>
                <p class="experience-date">May 2024 – July 2024</p>
                <ul class="list-disc ml-5 text-gray-700 text-sm">
                    <li>Extracted and analyzed 621 Chulalongkorn University patents and product data from 612 companies via web crawling.</li>
                    <li>Applied topic modeling techniques to identify key themes within the patent data.</li>
                    <li>Implemented a dual attention model to enhance the relationship mapping between textual data from patents and products.</li>
                    <li>Developed a patent-to-product recommendation system, identifying top 20 product keywords and top 3 firms for relevant suggestions.</li>
                </ul>
                <p class="mt-3">
                    <a href="pdf/Text mining by using Python2024 Report.pdf" class="link-button">More Detail</a>
                    </p>
            </div>

            <div class="experience-item">
                <h3 class="experience-title">Senior Project</h3>
                <p class="experience-date">January 2025 – April 2025</p>
                <ul class="list-disc ml-5 text-gray-700 text-sm">
                    <li>Evaluated the Thai reading comprehension proficiency of 5 Large Language Models (GPT-4o, Gemini Flash 2.0, DeepSeek V3, Typhoon2 8B/70B) using 3 Thai national exam datasets (A-Level, CU-TPT, O-NET), leveraging OpenRouter AI for API access and DSPy for prompting strategies.</li>
                    <li>Found that larger models achieved higher Exact Match Accuracy, and few-shot prompting significantly improved performance, particularly for smaller models like Typhoon2 8B (~34% accuracy increase).</li>
                    <li>Found that LLMs exceeded average human performance on less complex questions (up to 31% on O-NET M3, 25% on O-NET M6).</li>
                </ul>
                 <p class="mt-3">
                    <a href="pdf/Assessment of a Large Language Model’s Reading and Comprehension Proficiency in the Thai Language.pdf" class="link-button">More Detail</a>
                    </p>
            </div>
