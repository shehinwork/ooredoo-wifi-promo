<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home WiFi @310 Qr monthly - Blazing-Fast Internet</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
        .plan-card {
            background-color: #ffffff;
            padding: 2rem;
            border-radius: 0.75rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            border: 1px solid #e2e8f0;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            transition: transform 0.2s ease-in-out;
        }
        .plan-card:hover {
            transform: translateY(-5px);
        }
        .plan-card h3 {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }
        .plan-card .speed {
            font-size: 2.25rem;
            font-weight: 800;
            color: #dc2626; /* red-600 */
        }
        .plan-card .price {
            font-size: 1.875rem;
            font-weight: 700;
            margin-top: 0.5rem;
            color: #1e293b; /* slate-800 */
        }
        .plan-card ul {
            list-style: none;
            padding: 0;
            margin-top: 1rem;
            text-align: left;
            width: 100%;
        }
        .plan-card ul li {
            display: flex;
            align-items: center;
            margin-bottom: 0.5rem;
            color: #475569; /* slate-600 */
        }
        .plan-card ul li svg {
            margin-right: 0.5rem;
            color: #dc2626; /* red-600 */
        }
    </style>
</head>
<body class="bg-white text-gray-800">

    <header class="bg-white shadow-sm py-4">
        <div class="container mx-auto px-6 flex justify-center md:justify-start items-center">
            <span class="text-red-600 text-3xl font-bold">Ooredoo</span>
        </div>
    </header>

    <main class="container mx-auto px-6 py-8 md:py-12">

        <section id="home" class="text-center py-16 md:py-24">
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight leading-tight">
                🚀 Supercharge Your Home with 
                <span class="text-red-600">Blazing-Fast WiFi!</span>
            </h1>
            <p class="mt-4 text-lg md:text-xl text-gray-600 max-w-3xl mx-auto">
                Experience uninterrupted connectivity for streaming, gaming, and Browse. All for one incredible price.
            </p>
            <h2 class="mt-8 text-3xl md:text-4xl font-bold text-gray-900">
                ✨ Home WiFi @310 Qr monthly ✨
            </h2>
            <div class="mt-10 flex justify-center">
                 <a href="#get-connected" class="bg-red-600 text-white font-bold py-3 px-8 rounded-lg shadow-lg hover:bg-red-700 transition-transform transform hover:scale-105">
                    Get Started Now
                </a>
            </div>
        </section>

        <section id="features" class="py-16 md:py-20">
             <div class="text-center mb-12">
                <h2 class="text-3xl font-bold tracking-tight">Why Choose Ooredoo Home+?</h2>
                <p class="mt-2 text-gray-600">Get everything you need for a seamless and powerful home internet experience.</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 text-center">
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100">
                    <div class="text-4xl mb-4">⚡</div>
                    <h3 class="text-xl font-bold mb-2">Blazing-Fast Speeds</h3>
                    <p class="text-gray-600">Enjoy speeds up to 10 Gbps for 4K streaming, lag-free gaming, and smooth Browse.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100">
                    <div class="text-4xl mb-4">🛠️</div>
                    <h3 class="text-xl font-bold mb-2">Free Installation & Router</h3>
                    <p class="text-gray-600">Professional setup and a complimentary Wi-Fi router included with your plan.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100">
                    <div class="text-4xl mb-4">📞</div>
                    <h3 class="text-xl font-bold mb-2">No Landline Needed</h3>
                    <p class="text-gray-600">Enjoy dedicated fiber internet connectivity without the need for a traditional landline.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100">
                    <div class="text-4xl mb-4">📺</div>
                    <h3 class="text-xl font-bold mb-2">Ooredoo tv Included</h3>
                    <p class="text-gray-600">Access entertainment with Ooredoo tv App or TV box, depending on your chosen plan.</p>
                </div>
            </div>
        </section>

        <section id="plan-recommender" class="py-16 md:py-20 bg-gray-50 rounded-2xl">
            <div class="text-center mb-12 px-4">
                <h2 class="text-3xl font-bold tracking-tight">✨ Find Your Perfect Plan ✨</h2>
                <p class="mt-2 text-gray-600 max-w-2xl mx-auto">Let our AI help you discover the ideal Ooredoo Home+ plan tailored to your needs. Just tell us a bit about your usage!</p>
            </div>
            <div class="max-w-xl mx-auto bg-white p-8 rounded-xl shadow-md border border-gray-100">
                <form data-netlify="true" name="contact" class="space-y-6">
                    <input type="hidden" name="form-name" value="contact" />
                    <div hidden>
                        <label>
                            Don’t fill this out if you’re human: <input name="bot-field" />
                        </label>
                    </div>
                    <div>
                        <label for="numUsers" class="block text-sm font-medium text-gray-700">Number of People in Household</label>
                        <select id="numUsers" name="numUsers" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                            <option value="1-2">1-2 people</option>
                            <option value="3-4">3-4 people</option>
                            <option value="5+">5+ people</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700">Primary Internet Usage</label>
                        <div class="mt-2 space-y-2">
                            <div class="flex items-center">
                                <input type="checkbox" id="usageStreaming" name="usage" value="streaming" class="h-4 w-4 text-red-600 border-gray-300 rounded focus:ring-red-500">
                                <label for="usageStreaming" class="ml-2 text-sm text-gray-700">Streaming (Netflix, YouTube, etc.)</label>
                            </div>
                            <div class="flex items-center">
                                <input type="checkbox" id="usageGaming" name="usage" value="gaming" class="h-4 w-4 text-red-600 border-gray-300 rounded focus:ring-red-500">
                                <label for="usageGaming" class="ml-2 text-sm text-gray-700">Online Gaming</label>
                            </div>
                            <div class="flex items-center">
                                <input type="checkbox" id="usageWork" name="usage" value="work" class="h-4 w-4 text-red-600 border-gray-300 rounded focus:ring-red-500">
                                <label for="usageWork" class="ml-2 text-sm text-gray-700">Work/Study from Home (Video Calls, Large Downloads)</label>
                            </div>
                            <div class="flex items-center">
                                <input type="checkbox" id="usageBrowse" name="usage" value="Browse" class="h-4 w-4 text-red-600 border-gray-300 rounded focus:ring-red-500">
                                <label for="usageBrowse" class="ml-2 text-sm text-gray-700">General Browse & Social Media</label>
                            </div>
                        </div>
                    </div>
                    <div>
                        <button type="submit" id="getRecommendationBtn" class="w-full flex justify-center py-3 px-4 border border-transparent rounded-md shadow-sm text-lg font-medium text-white bg-red-600 hover:bg-red-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-red-500 transition-transform transform hover:scale-105">
                            Get Recommendation ✨
                        </button>
                    </div>
                    <div id="recommendationResult" class="mt-6 p-4 bg-red-50 border border-red-200 rounded-md text-gray-700 hidden">
                        <p class="font-semibold mb-2">Our Recommendation:</p>
                        <div id="recommendationText" class="text-sm"></div>
                        <div id="loadingIndicator" class="text-center mt-4 hidden">
                            <div class="animate-spin rounded-full h-8 w-8 border-b-2 border-red-600 mx-auto"></div>
                            <p class="text-sm text-gray-500 mt-2">Generating your personalized recommendation...</p>
                        </div>
                    </div>
                </form>
            </div>
        </section>

        <section id="ooredoo-plans" class="py-16 md:py-20 bg-red-50 rounded-2xl">
            <div class="text-center mb-12 px-4">
                <h2 class="text-3xl font-bold tracking-tight">Explore Ooredoo Home+ Plans</h2>
                <p class="mt-2 text-gray-600 max-w-2xl mx-auto">Discover the perfect internet package for your home. From basic Browse to ultimate gaming, we have a plan that fits your needs.</p>
            </div>
            <div id="plans-grid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 px-4">
                </div>
        </section>
        
        <section id="comparison" class="py-16 md:py-20">
             <div class="text-center mb-12 px-4">
                <h2 class="text-3xl font-bold tracking-tight">See How We Compare</h2>
                <p class="mt-2 text-gray-600 max-w-2xl mx-auto">We're confident you won't find a better deal. Our plan is designed to give you the most speed and value for your money, beating the competition.</p>
            </div>
            <div class="chart-container">
                <canvas id="comparisonChart"></canvas>
            </div>
        </section>

        <section id="get-connected" class="py-16 md:py-20 bg-red-50 rounded-2xl">
            <div class="text-center mb-12 px-4">
                <h2 class="text-3xl font-bold tracking-tight">Get Connected Today!</h2>
                <p class="mt-2 text-gray-600 max-w-2xl mx-auto">Fill out the form below and our team will get in touch with you to help set up your new Home WiFi connection.</p>
            </div>
            <div class="max-w-xl mx-auto bg-white p-8 rounded-xl shadow-md border border-gray-100">
                <form data-netlify="true" name="contactForm" class="space-y-6">
                    <input type="hidden" name="form-name" value="contactForm" />
                    <div hidden>
                        <label>
                            Don’t fill this out if you’re human: <input name="bot-field" />
                        </label>
                    </div>
                    <div>
                        <label for="qatarId" class="block text-sm font-medium text-gray-700">Qatar ID Number</label>
                        <input type="text" id="qatarId" name="qatarId" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                    </div>
                    <div>
                        <label for="buildingNumber" class="block text-sm font-medium text-gray-700">Building Number</label>
                        <input type="text" id="buildingNumber" name="buildingNumber" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                    </div>
                    <div>
                        <label for="zoneNumber" class="block text-sm font-medium text-gray-700">Zone Number</label>
                        <input type="text" id="zoneNumber" name="zoneNumber" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                    </div>
                    <div>
                        <label for="streetNumber" class="block text-sm font-medium text-gray-700">Street Number</label>
                        <input type="text" id="streetNumber" name="streetNumber" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                    </div>
                    <div>
                        <label for="electricityNumber" class="block text-sm font-medium text-gray-700">Electricity Number</label>
                        <input type="text" id="electricityNumber" name="electricityNumber" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                    </div>
                    <div>
                        <label for="contactNumber" class="block text-sm font-medium text-gray-700">Contact Number</label>
                        <input type="tel" id="contactNumber" name="contactNumber" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                    </div>
                    <div>
                        <button type="submit" class="w-full flex justify-center py-3 px-4 border border-transparent rounded-md shadow-sm text-lg font-medium text-white bg-red-600 hover:bg-red-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-red-500 transition-transform transform hover:scale-105">
                            Submit Details
                        </button>
                    </div>
                    <div id="formMessage" class="text-center mt-4 text-sm font-medium"></div>
                </form>
            </div>
        </section>

        <section id="download" class="py-20 md:py-24">
            <div class="bg-red-900 text-white rounded-2xl p-8 md:p-16 text-center shadow-2xl">
                 <h2 class="text-3xl md:text-4xl font-extrabold tracking-tight">Connect with us!</h2>
                 <p class="mt-4 text-red-100 max-w-2xl mx-auto">Reach out to us on WhatsApp for any inquiries or support. We're here to help you get the best out of your Home WiFi experience.</p>
                <p class="mt-12 font-bold text-red-300">Connect with us on WhatsApp!</p>
                <div class="flex justify-center mt-4">
                    <canvas id="whatsappQrCodeCanvas" class="bg-white p-2 rounded-lg"></canvas>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-red-100 border-t border-red-200">
        <div class="container mx-auto px-6 py-6 text-center text-gray-500">
            <p>&copy; 2025 Home WiFi @310 Qr monthly. All Rights Reserved.</p>
            <p class="mt-2 text-sm">
                <a href="#" class="hover:text-red-600">YourWebsite.com</a> | Follow Us: 
                <a href="#" class="hover:text-red-600">@HomeWiFi310QRmonthly</a>
            </p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            
            function drawQrCode(canvasId, text) {
                const canvas = document.getElementById(canvasId);
                if (!canvas) return;
                const ctx = canvas.getContext('2d');
                const size = 160;
                canvas.width = size;
                canvas.height = size;
                ctx.clearRect(0, 0, size, size);
                
                const boxSize = 8;
                const numBoxes = size / boxSize;
                
                for (let i = 0; i < numBoxes; i++) {
                    for (let j = 0; j < numBoxes; j++) {
                        if (Math.random() > 0.5) { 
                            ctx.fillStyle = '#1e293b'; 
                            ctx.fillRect(i * boxSize, j * boxSize, boxSize, boxSize);
                        }
                    }
                }
                
                ctx.fillStyle = '#1e293b';
                ctx.fillRect(boxSize, boxSize, boxSize * 7, boxSize);
                ctx.fillRect(boxSize, boxSize, boxSize, boxSize * 7);
                ctx.fillRect(boxSize * 7, boxSize, boxSize, boxSize * 7);
                ctx.fillRect(boxSize, boxSize * 7, boxSize * 7, boxSize);
                ctx.fillRect(boxSize*3, boxSize*3, boxSize * 3, boxSize * 3);
            }

            drawQrCode('whatsappQrCodeCanvas', 'https://wa.me/974xxxxxxx'); // Placeholder for WhatsApp number

            const ctx = document.getElementById('comparisonChart');
            if(ctx) {
                new Chart(ctx, {
                    type: 'bar',
                    data: {
                        labels: ['Price (QR/Month)', 'Max Speed (Mbps)'],
                        datasets: [{
                            label: 'Home WiFi @310 Qr monthly',
                            data: [310, 500],
                            backgroundColor: 'rgb(220, 38, 38)', // red-600
                            borderColor: 'rgb(185, 28, 28)', // red-700
                            borderWidth: 1,
                            borderRadius: 4
                        },
                        {
                            label: 'Competitor A',
                            data: [350, 400],
                            backgroundColor: 'rgba(156, 163, 175, 0.7)', // gray-400
                            borderColor: 'rgb(107, 114, 128)', // gray-500
                            borderWidth: 1,
                            borderRadius: 4
                        },
                        {
                            label: 'Competitor B',
                            data: [320, 250],
                            backgroundColor: 'rgba(209, 213, 219, 0.7)', // gray-200
                            borderColor: 'rgb(156, 163, 175)', // gray-400
                            borderWidth: 1,
                            borderRadius: 4
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        indexAxis: 'y',
                        scales: {
                            x: {
                                beginAtZero: true,
                                grid: {
                                    color: 'rgba(0, 0, 0, 0.05)'
                                }
                            },
                             y: {
                                grid: {
                                    display: false
                                }
                            }
                        },
                        plugins: {
                            legend: {
                                position: 'bottom',
                            },
                            tooltip: {
                                backgroundColor: '#1e293b',
                                titleFont: {
                                    weight: 'bold'
                                },
                                bodyFont: {
                                    size: 14
                                },
                                callbacks: {
                                    label: function(context) {
                                        let label = context.dataset.label || '';
                                        if (label) {
                                            label += ': ';
                                        }
                                        if (context.parsed.x !== null) {
                                            if(context.datasetIndex === 0 && context.dataIndex === 0) {
                                                label += context.parsed.x + ' QR';
                                            } else {
                                                label += context.parsed.x + ' Mbps';
                                            }
                                        }
                                        return label;
                                    }
                                }
                            }
                        }
                    }
                });
            }

            // Ooredoo Home+ Plans Data
            const ooredooPlans = [
                {
                    name: "GO",
                    speed: "1 Gbps",
                    monthlyFee: "QR 310",
                    contract: "Over 12 months",
                    features: [
                        "Wi-Fi router",
                        "Ooredoo tv App",
                        "0 credits"
                    ]
                },
                {
                    name: "GO Ent",
                    speed: "1 Gbps",
                    monthlyFee: "QR 320",
                    contract: "Over 12 months",
                    features: [
                        "Wi-Fi router",
                        "Ooredoo tv App",
                        "5 credits"
                    ]
                },
                {
                    name: "Prime",
                    speed: "1 Gbps",
                    monthlyFee: "QR 455",
                    contract: "Over 12 months",
                    features: [
                        "2 Wi-Fi routers",
                        "Ooredoo tv box",
                        "40 credits"
                    ]
                },
                {
                    name: "Super",
                    speed: "1 Gbps",
                    monthlyFee: "QR 950",
                    contract: "Over 12 months",
                    features: [
                        "Fibre connected rooms",
                        "2 Ooredoo tv boxes",
                        "60 credits"
                    ]
                },
                {
                    name: "ELITE",
                    speed: "10 Gbps",
                    monthlyFee: "QR 6500",
                    contract: "Over 12 months",
                    features: [
                        "5 Fibre connected rooms",
                        "Ooredoo tv boxes",
                        "100 credits"
                    ]
                }
            ];

            const plansGrid = document.getElementById('plans-grid');
            if (plansGrid) {
                ooredooPlans.forEach(plan => {
                    const planCard = document.createElement('div');
                    planCard.className = 'plan-card';
                    planCard.innerHTML = `
                        <h3 class="text-gray-900">${plan.name}</h3>
                        <p class="speed">${plan.speed}</p>
                        <p class="price">${plan.monthlyFee}</p>
                        <p class="text-sm text-gray-500 mt-1">${plan.contract}</p>
                        <ul class="mt-4 text-sm">
                            ${plan.features.map(feature => `
                                <li>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                                    </svg>
                                    ${feature}
                                </li>
                            `).join('')}
                        </ul>
                    `;
                    plansGrid.appendChild(planCard);
                });
            }

            // Contact Form Submission
            const contactForm = document.querySelector('form[name="contactForm"]'); // Select by name for Netlify Forms
            const formMessage = document.getElementById('formMessage');

            if (contactForm && formMessage) {
                contactForm.addEventListener('submit', function(event) {
                    // Prevent default submission for testing purposes with Netlify Forms,
                    // as Netlify handles the actual submission.
                    // If you want to see a local message, you can keep this.
                    // For Netlify, the browser will typically redirect to a success page or display Netlify's message.
                    event.preventDefault(); 
                    
                    const formData = {
                        qatarId: contactForm.querySelector('#qatarId').value,
                        buildingNumber: contactForm.querySelector('#buildingNumber').value,
                        zoneNumber: contactForm.querySelector('#zoneNumber').value,
                        streetNumber: contactForm.querySelector('#streetNumber').value,
                        electricityNumber: contactForm.querySelector('#electricityNumber').value,
                        contactNumber: contactForm.querySelector('#contactNumber').value
                    };

                    console.log('Form Data Submitted (handled by Netlify Forms):', formData);
                    formMessage.textContent = 'Thank you! Your details have been submitted. Our team will contact you shortly.';
                    formMessage.className = 'text-center mt-4 text-sm font-medium text-green-600';
                    contactForm.reset();
                    // In a real Netlify deployment, this local JavaScript handler would be superseded
                    // by Netlify's form processing, which might redirect or show their own success message.
                    // For local testing of the UI, this is fine.
                });
            }

            // LLM Integration for Plan Recommender
            const recommenderForm = document.querySelector('form[name="contact"]'); // Select by name for Netlify Forms
            const recommendationResult = document.getElementById('recommendationResult');
            const recommendationText = document.getElementById('recommendationText');
            const loadingIndicator = document.getElementById('loadingIndicator');

            if (recommenderForm) {
                recommenderForm.addEventListener('submit', async function(event) {
                    event.preventDefault();

                    recommendationResult.classList.add('hidden');
                    loadingIndicator.classList.remove('hidden');
                    recommendationText.textContent = '';

                    const numUsers = document.getElementById('numUsers').value;
                    const primaryUsages = Array.from(recommenderForm.querySelectorAll('input[name="usage"]:checked'))
                                            .map(cb => cb.value)
                                            .join(', ') || 'general Browse';

                    const availablePlans = ooredooPlans.map(plan => {
                        return `${plan.name} Plan: Speed ${plan.speed}, Monthly Fee ${plan.monthlyFee}, Features: ${plan.features.join(', ')}.`;
                    }).join('\n');

                    const prompt = `You are a helpful Ooredoo Home Internet plan recommender. A user is looking for a home internet plan with the following characteristics:
- Number of people in household: ${numUsers}
- Primary internet usage: ${primaryUsages}

Here are the available Ooredoo Home+ plans:
${availablePlans}

Based on these details, recommend the single best Ooredoo plan for the user. Explain why you chose this plan based on their needs and the plan's features. Be concise and focus on the most relevant aspects.`;

                    try {
                        let chatHistory = [];
                        chatHistory.push({ role: "user", parts: [{ text: prompt }] });
                        const payload = { contents: chatHistory };
                        const apiKey = ""; // IMPORTANT: Replace with your actual Gemini API Key
                        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

                        const response = await fetch(apiUrl, {
                            method: 'POST',
                            headers: { 'Content-Type': 'application/json' },
                            body: JSON.stringify(payload)
                        });

                        const result = await response.json();
                        if (result.candidates && result.candidates.length > 0 &&
                            result.candidates[0].content && result.candidates[0].content.parts &&
                            result.candidates[0].content.parts.length > 0) {
                            const text = result.candidates[0].content.parts[0].text;
                            recommendationText.textContent = text;
                        } else {
                            recommendationText.textContent = 'Sorry, I could not generate a recommendation at this time. Please try again.';
                        }
                    } catch (error) {
                        console.error('Error calling Gemini API:', error);
                        recommendationText.textContent = 'An error occurred while fetching the recommendation. Please try again later.';
                    } finally {
                        loadingIndicator.classList.add('hidden');
                        recommendationResult.classList.remove('hidden');
                    }
                });
            }
        });
    </script>

</body>
</html>
