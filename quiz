<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strategic Style: Your Life Design Style Self-Reflection</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f8f8; /* Light gray background */
        }
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Playfair Display', serif;
        }
        /* Custom colors based on user prompt */
        .bg-primary { background-color: #007BFF; } /* Blue */
        .text-primary { color: #007BFF; }
        .border-primary { border-color: #007BFF; }

        .bg-secondary { background-color: #28A745; } /* Green */
        .text-secondary { color: #28A745; }

        .bg-accent { background-color: #FFC107; } /* Amber */
        .text-accent { color: #FFC107; }

        .btn-shadow {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.08);
        }
        .btn-hover:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15), 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .custom-radio input[type="radio"] {
            display: none;
        }
        .custom-radio label {
            display: block;
            padding: 1rem;
            border: 2px solid #e2e8f0; /* default border */
            border-radius: 0.75rem; /* rounded-xl equivalent */
            cursor: pointer;
            transition: all 0.2s ease-in-out;
            text-align: left;
            margin-bottom: 0.75rem;
            font-size: 1.125rem; /* text-lg equivalent */
            line-height: 1.75rem; /* leading-7 equivalent */
            color: #4a5568; /* text-gray-700 equivalent */
            box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05); /* shadow-sm equivalent */
        }
        .custom-radio label:hover {
            border-color: #cbd5e0; /* gray-400 on hover */
            background-color: #f7fafc; /* gray-50 on hover */
        }
        .custom-radio input[type="radio"]:checked + label {
            border-color: #007BFF; /* primary blue */
            background-color: #e0f2fe; /* blue-100 equivalent for selected */
            color: #007BFF;
            box-shadow: 0 4px 6px rgba(0, 123, 255, 0.1), 0 1px 3px rgba(0, 123, 255, 0.08); /* subtle blue shadow */
        }
        .form-input {
            width: 100%;
            padding: 0.75rem 1rem;
            border: 2px solid #e2e8f0;
            border-radius: 0.75rem;
            font-size: 1.125rem;
            line-height: 1.75rem;
            color: #4a5568;
            transition: all 0.2s ease-in-out;
            box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
        }
        .form-input:focus {
            outline: none;
            border-color: #007BFF;
            box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.25);
        }
        .btn-base {
            padding: 0.75rem 1.5rem;
            border-radius: 0.75rem;
            font-weight: 600;
            transition: all 0.2s ease-in-out;
            cursor: pointer;
        }
        .btn-primary-filled {
            background-color: #007BFF;
            color: white;
            box-shadow: 0 4px 6px rgba(0, 123, 255, 0.15), 0 1px 3px rgba(0, 123, 255, 0.08);
        }
        .btn-primary-filled:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
        .btn-secondary-outline {
            border: 2px solid #28A745;
            color: #28A745;
            background-color: transparent;
        }
        .btn-secondary-outline:hover {
            background-color: #e6ffe6; /* Light green on hover */
            color: #28A745;
        }
        .progress-bar-container {
            width: 100%;
            background-color: #e2e8f0;
            border-radius: 9999px; /* Full rounded */
            height: 0.75rem; /* h-3 */
            overflow: hidden;
            margin-top: 1.5rem; /* mt-6 */
        }
        .progress-bar {
            height: 100%;
            background-color: #007BFF; /* primary blue */
            border-radius: 9999px;
            transition: width 0.3s ease-in-out;
        }
        .error-message {
            color: #dc3545; /* Red for errors */
            background-color: #f8d7da; /* Light red background */
            border: 1px solid #f5c6cb;
            border-radius: 0.5rem;
            padding: 0.75rem 1rem;
            margin-top: 1rem;
            font-size: 0.9rem;
            text-align: center;
        }
        .loading-spinner {
            border: 4px solid rgba(255, 255, 255, 0.3);
            border-top: 4px solid #fff;
            border-radius: 50%;
            width: 1.5rem;
            height: 1.5rem;
            animation: spin 1s linear infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="flex flex-col items-center justify-center min-h-screen text-gray-800 p-4 sm:p-6 lg:p-8">

    <div class="max-w-4xl w-full bg-white rounded-xl shadow-lg p-6 sm:p-8 lg:p-10 text-center">

        <!-- Logo/Brand Name -->
        <div class="mb-6">
            <h2 class="text-3xl sm:text-4xl text-gray-700 font-bold">Strategic Style</h2>
            <p class="text-lg sm:text-xl text-gray-500 mt-2">Design Your Intentional Life</p>
        </div>

        <!-- Landing Page Section -->
        <div id="landing-page" class="transition-opacity duration-500 ease-in-out">
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold text-primary mb-6 leading-tight">
                Your Life Design Style:
                <span class="block text-gray-800 mt-2">Discover How You're Crafting Your Intentional Life!</span>
            </h1>

            <p class="text-lg sm:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                Welcome to Strategic Style! Do you feel like you're reacting to life, or actively designing it? Take a few moments for self-reflection to uncover *your* unique 'Life Design Style' and unlock insights on how to create the purposeful, impactful life you truly desire. Move from chaos to calm, focus, and proactive living!
            </p>

            <!-- Benefits Section -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-10">
                <div class="p-5 bg-blue-50 rounded-lg shadow-sm">
                    <h3 class="text-xl font-semibold text-primary mb-2">Clarify Your Vision</h3>
                    <p class="text-gray-600">Pinpoint what truly matters and align your actions with your deepest aspirations.</p>
                </div>
                <div class="p-5 bg-green-50 rounded-lg shadow-sm">
                    <h3 class="text-xl font-semibold text-secondary mb-2">Unlock Your Potential</h3>
                    <p class="text-gray-600">Identify your strengths and areas for growth to maximize your impact.</p>
                </div>
                <div class="p-5 bg-yellow-50 rounded-lg shadow-sm">
                    <h3 class="text-xl font-semibold text-accent mb-2">Live with Purpose</h3>
                    <p class="text-gray-600">Gain actionable steps to design a life that's intentionally yours, not just happening to you.</p>
                </div>
            </div>

            <!-- Call to Action -->
            <h2 class="text-3xl sm:text-4xl font-bold text-gray-800 mb-6">
                Ready to Design Your Future?
            </h2>

            <button id="start-quiz-btn" class="btn-base btn-primary-filled btn-shadow btn-hover text-2xl sm:text-3xl px-8 py-4">
                Start Your Reflection!
            </button>
        </div>

        <!-- Quiz Section -->
        <div id="quiz-section" class="hidden transition-opacity duration-500 ease-in-out text-left">
            <h2 class="text-3xl sm:text-4xl font-bold text-primary mb-6 text-center">
                Your Life Design Style: Self-Reflection
            </h2>

            <div class="progress-bar-container">
                <div id="progress-bar" class="progress-bar" style="width: 0%;"></div>
            </div>
            <p id="progress-text" class="text-sm text-gray-500 text-right mt-2 mb-6"></p>

            <div id="question-container" class="mb-8">
                <!-- Questions will be dynamically loaded here -->
            </div>

            <div id="text-input-container" class="hidden mb-8">
                <label for="text-input" class="block text-xl font-semibold text-gray-800 mb-4"></label>
                <input type="text" id="text-input" class="form-input" placeholder="Type your answer here..." />
            </div>

            <div class="flex justify-between items-center mt-8">
                <button id="prev-btn" class="btn-base btn-secondary-outline btn-hover hidden">Previous</button>
                <button id="next-btn" class="btn-base btn-primary-filled btn-hover ml-auto">Next</button>
            </div>
            <p id="error-message-quiz" class="error-message hidden"></p>
        </div>

        <!-- Email Capture Section -->
        <div id="email-capture-section" class="hidden transition-opacity duration-500 ease-in-out">
            <h2 class="text-3xl sm:text-4xl font-bold text-primary mb-6 text-center">
                Unlock Your Personalized Insights!
            </h2>
            <p class="text-lg sm:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                Enter your email below to receive your unique 'Life Design Style' breakdown and tailored resources from Strategic Style.
            </p>
            <div class="max-w-md mx-auto">
                <input type="email" id="email-input" class="form-input mb-4" placeholder="Your Email Address" required>
                <input type="text" id="first-name-input" class="form-input mb-6" placeholder="Your First Name (Optional)">
                <button id="submit-email-btn" class="btn-base btn-primary-filled btn-hover w-full flex items-center justify-center">
                    <span id="submit-email-text">Get My Insights!</span>
                    <div id="submit-email-spinner" class="loading-spinner ml-3 hidden"></div>
                </button>
                <p id="email-error-message" class="error-message hidden"></p>
            </div>
        </div>

        <!-- Thank You / Results Section -->
        <div id="thank-you-section" class="hidden transition-opacity duration-500 ease-in-out">
            <h2 class="text-3xl sm:text-4xl font-bold text-primary mb-6 text-center">
                Thank You for Your Reflection!
            </h2>
            <p class="text-lg sm:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                We're thrilled you took this empowering step for yourself. We're now crafting personalized insights and resources tailored to *your* unique 'Life Design Style.' Keep an eye on your inbox for tools to help you plan today for your future and live with purpose!
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#" id="planner-link" class="btn-base btn-primary-filled btn-hover text-lg flex-1">Explore Our Goal Setting Planner</a>
                <a href="#" id="community-link" class="btn-base btn-secondary-outline btn-hover text-lg flex-1">Join Our Strategic Style Community</a>
            </div>
        </div>

        <!-- Secondary CTA/Footer Note -->
        <p class="text-md sm:text-lg text-gray-600 mt-8">
            &copy; 2025 Strategic Style. Plan today for your future. Unlock Your Potential. Live with Purpose.
        </p>

    </div>

    <script type="module">
        // MAKE SURE TO REPLACE THIS WITH YOUR ACTUAL MAKE.COM WEBHOOK URL
        const WEBHOOK_URL = "https://hook.us2.make.com/j6r43j7y0b466cj9v7yh0qbn251244uh";

        // --- Quiz Logic ---
        const questions = [
            {
                question: "When you think about your ideal future, what's your primary feeling or approach?",
                type: "radio",
                options: [
                    "I have a clear vision, but sometimes struggle with the path to get there.",
                    "I have many ideas, but they often feel chaotic or overwhelming.",
                    "I tend to go with the flow, hoping things work out rather than planning.",
                    "I'm constantly refining and optimizing, always seeking greater impact."
                ],
                answer: null
            },
            {
                question: "How do you typically approach setting new goals or intentions for your life?",
                type: "radio",
                options: [
                    "I prefer structured, step-by-step methods to ensure I'm thorough.",
                    "I'm more intuitive and spontaneous, often starting without a rigid plan.",
                    "I think about what feels good or right, prioritizing personal alignment over strict objectives.",
                    "I immediately look for the most efficient path to achieve significant results."
                ],
                answer: null
            },
            {
                question: "When it comes to your daily routines and habits, how would you describe them?",
                type: "radio",
                options: [
                    "I aim for consistency, but often get derailed by unexpected events.",
                    "They're often changing or non-existent; I struggle with consistency.",
                    "I have some habits, but they're not always intentional or aligned with my goals.",
                    "My routines are mostly dialed in, but I'm always looking for ways to optimize."
                ],
                answer: null
            },
            {
                question: "What's your biggest frustration when trying to make progress in an important area of your life?",
                type: "radio",
                options: [
                    "Overwhelm from too many tasks or unclear priorities.",
                    "Lacking a clear direction or starting point.",
                    "Feeling reactive and easily distracted, losing focus.",
                    "Not seeing results quickly enough or maximizing my potential."
                ],
                answer: null
            },
            {
                question: "How do you feel about the idea of actively 'designing' your life, rather than just living it?",
                type: "radio",
                options: [
                    "It's a concept I believe in, but I need practical guidance to implement it.",
                    "It sounds empowering, but also a bit daunting. Where do I even begin?",
                    "I'm intrigued; I often feel like I'm not fully in control of my time/energy.",
                    "I'm already doing this to some extent and want to refine my approach."
                ],
                answer: null
            },
            {
                question: "When you achieve a personal goal, what's your primary feeling?",
                type: "radio",
                options: [
                    "Satisfaction from successfully executing a plan.",
                    "Excitement about the new possibilities it opens up.",
                    "Gratitude for the journey and the connections made along the way.",
                    "Motivation to immediately tackle the next big thing."
                ],
                answer: null
            },
            {
                question: "What is one specific area of your life you are most eager to intentionally design or improve right now?",
                type: "text",
                answer: null
            }
        ];

        let currentQuestionIndex = 0;

        // DOM Elements
        const landingPage = document.getElementById('landing-page');
        const quizSection = document.getElementById('quiz-section');
        const emailCaptureSection = document.getElementById('email-capture-section');
        const thankYouSection = document.getElementById('thank-you-section');

        const startQuizBtn = document.getElementById('start-quiz-btn');
        const questionContainer = document.getElementById('question-container');
        const textInputContainer = document.getElementById('text-input-container');
        const textInputLabel = textInputContainer.querySelector('label');
        const textInput = document.getElementById('text-input');

        const prevBtn = document.getElementById('prev-btn');
        const nextBtn = document.getElementById('next-btn');
        const progressBar = document.getElementById('progress-bar');
        const progressText = document.getElementById('progress-text');

        const emailInput = document.getElementById('email-input');
        const firstNameInput = document.getElementById('first-name-input');
        const submitEmailBtn = document.getElementById('submit-email-btn');
        const submitEmailText = document.getElementById('submit-email-text');
        const submitEmailSpinner = document.getElementById('submit-email-spinner');

        const errorMessageQuiz = document.getElementById('error-message-quiz');
        const emailErrorMessage = document.getElementById('email-error-message');

        // Placeholder for real links (MAKE SURE TO REPLACE THESE WITH YOUR ACTUAL LINKS)
        const plannerLink = document.getElementById('planner-link');
        const communityLink = document.getElementById('community-link');

        // Update placeholder links
        plannerLink.href = "https://example.com/goal-setting-planner"; // https://buymeacoffee.com/strategicstyle/e/423801
        communityLink.href = "https://example.com/strategic-style-community"; // https://x.com/i/communities/1760194232684532009

        const showPage = (pageToShow) => {
            landingPage.classList.add('hidden');
            quizSection.classList.add('hidden');
            emailCaptureSection.classList.add('hidden');
            thankYouSection.classList.add('hidden');

            pageToShow.classList.remove('hidden');
        };

        const renderQuestion = () => {
            const q = questions[currentQuestionIndex];
            questionContainer.innerHTML = ''; // Clear previous question

            // Update progress bar and text
            const progress = ((currentQuestionIndex + 1) / questions.length) * 100;
            progressBar.style.width = `${progress}%`;
            progressText.textContent = `Question ${currentQuestionIndex + 1} of ${questions.length}`;

            // Hide/Show text input
            if (q.type === 'text') {
                textInputContainer.classList.remove('hidden');
                textInputLabel.textContent = q.question;
                textInput.value = q.answer || ''; // Populate if already answered
                questionContainer.classList.add('hidden'); // Hide radio options
                textInput.focus();
            } else {
                textInputContainer.classList.add('hidden');
                questionContainer.classList.remove('hidden'); // Show radio options
                const questionHtml = `<h3 class="text-xl sm:text-2xl font-semibold text-gray-800 mb-6">${q.question}</h3>`;
                questionContainer.innerHTML = questionHtml;

                q.options.forEach((option, index) => {
                    const optionId = `q${currentQuestionIndex}-option${index}`;
                    const checked = (q.answer === option) ? 'checked' : '';
                    questionContainer.innerHTML += `
                        <div class="custom-radio">
                            <input type="radio" id="${optionId}" name="question-${currentQuestionIndex}" value="${option}" ${checked}>
                            <label for="${optionId}">${option}</label>
                        </div>
                    `;
                });
            }

            // Button visibility
            prevBtn.classList.toggle('hidden', currentQuestionIndex === 0);
        };

        const getSelectedAnswer = () => {
            const q = questions[currentQuestionIndex];
            if (q.type === 'text') {
                return textInput.value.trim();
            } else {
                const selectedRadio = document.querySelector(`input[name="question-${currentQuestionIndex}"]:checked`);
                return selectedRadio ? selectedRadio.value : null;
            }
        };

        const validateCurrentAnswer = () => {
            const answer = getSelectedAnswer();
            const q = questions[currentQuestionIndex];
            if (q.type === 'text') {
                return answer !== '';
            } else {
                return answer !== null;
            }
        };

        const nextQuestion = () => {
            errorMessageQuiz.classList.add('hidden'); // Hide previous errors

            if (!validateCurrentAnswer()) {
                errorMessageQuiz.textContent = "Please select an answer or fill in the text field to continue.";
                errorMessageQuiz.classList.remove('hidden');
                return;
            }

            // Save the current answer
            questions[currentQuestionIndex].answer = getSelectedAnswer();

            if (currentQuestionIndex < questions.length - 1) {
                currentQuestionIndex++;
                renderQuestion();
            } else {
                // End of quiz, show email capture
                showPage(emailCaptureSection);
            }
        };

        const prevQuestion = () => {
            errorMessageQuiz.classList.add('hidden'); // Hide previous errors
            if (currentQuestionIndex > 0) {
                currentQuestionIndex--;
                renderQuestion();
            }
        };

        const sendQuizResponsesToWebhook = async (email, firstName) => {
            try {
                submitEmailBtn.disabled = true;
                submitEmailText.classList.add('hidden');
                submitEmailSpinner.classList.remove('hidden');
                emailErrorMessage.classList.add('hidden');

                const responses = questions.map(q => ({
                    question: q.question,
                    answer: q.answer
                }));

                // Generate a simple unique ID for this submission (since Firebase userId is not used here)
                const submissionId = crypto.randomUUID(); 

                const webhookPayload = {
                    email: email,
                    firstName: firstName,
                    submissionId: submissionId, // Unique ID for this submission
                    timestamp: new Date().toISOString(), 
                    responses: responses,
                    quizVersion: "Life Design Style V1",
                    source: "StrategicStyleQuiz" // A static source identifier
                };

                const webhookResponse = await fetch(WEBHOOK_URL, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json'
                    },
                    body: JSON.stringify(webhookPayload)
                });

                if (webhookResponse.ok) {
                    console.log("Quiz responses sent to Make.com webhook successfully!");
                    showPage(thankYouSection); // Show thank you page on success
                } else {
                    console.error("Error sending to Make.com webhook:", webhookResponse.status, webhookResponse.statusText);
                    // Attempt to parse error details if available
                    try {
                        const errorData = await webhookResponse.json();
                        console.error("Webhook error details:", errorData);
                        emailErrorMessage.textContent = `Submission failed: ${errorData.message || 'Unknown error from webhook.'}`;
                    } catch (e) {
                        emailErrorMessage.textContent = "Submission failed: Please try again.";
                    }
                    emailErrorMessage.classList.remove('hidden');
                }
            } catch (overallError) {
                console.error("Overall error during submission: ", overallError);
                emailErrorMessage.textContent = "An unexpected error occurred. Please check your internet connection and try again.";
                emailErrorMessage.classList.remove('hidden');
            } finally {
                submitEmailBtn.disabled = false;
                submitEmailText.classList.remove('hidden');
                submitEmailSpinner.classList.add('hidden');
            }
        };

        // Event Listeners
        startQuizBtn.addEventListener('click', () => {
            showPage(quizSection);
            currentQuestionIndex = 0; // Reset or ensure it starts from 0
            renderQuestion();
        });

        nextBtn.addEventListener('click', nextQuestion);
        prevBtn.addEventListener('click', prevQuestion);

        submitEmailBtn.addEventListener('click', () => {
            emailErrorMessage.classList.add('hidden');
            const email = emailInput.value.trim();
            const firstName = firstNameInput.value.trim();

            if (!email) {
                emailErrorMessage.textContent = "Email address is required.";
                emailErrorMessage.classList.remove('hidden');
                return;
            }
            if (!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)) {
                emailErrorMessage.textContent = "Please enter a valid email address.";
                emailErrorMessage.classList.remove('hidden');
                return;
            }

            // Call the function to send data to webhook
            sendQuizResponsesToWebhook(email, firstName);
        });
    </script>
</body>
</html>
