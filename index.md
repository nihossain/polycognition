<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Polycognition AI: Autonomous, Defect-Free Injection Molding</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F9FA;
            color: #212529;
        }
        .text-primary { color: #6D47D9; }
        .bg-primary { background-color: #6D47D9; }
        .border-primary { border-color: #6D47D9; }
        .text-secondary { color: #EC407A; }
        .bg-secondary { background-color: #EC407A; }
        .text-tertiary { color: #AB47BC; }
        .bg-tertiary { background-color: #AB47BC; }
        .text-accent { color: #26A69A; }
        .bg-accent { background-color: #26A69A; }
        .text-accent2 { color: #FF7043; }
        .bg-accent2 { background-color: #FF7043; }
        .bg-dark-gray { background-color: #2A2D34; }

        .stat-card {
            background-color: white;
            border-radius: 0.75rem;
            padding: 1.5rem;
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            border-left: 5px solid;
            height: 100%;
        }
        .flow-step {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            flex: 1;
            padding: 1rem;
            border-radius: 0.75rem;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .flow-step:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
        }
        .icon-large {
            font-size: 3rem;
            margin-bottom: 0.75rem;
        }
    </style>
</head>
<body class="bg-[#F8F9FA]">

    <header class="bg-dark-gray text-white py-6 px-4 md:px-8 shadow-lg">
        <nav class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-3xl font-extrabold text-primary">Polycognition AI</a>
            <div class="hidden md:flex space-x-6">
                <a href="#problem" class="text-gray-300 hover:text-white transition-colors duration-200">Problem</a>
                <a href="#solution" class="text-gray-300 hover:text-white transition-colors duration-200">Solution</a>
                <a href="#benefits" class="text-gray-300 hover:text-white transition-colors duration-200">Benefits</a>
                <a href="#contact" class="bg-primary hover:bg-[#5E35B1] text-white py-2 px-4 rounded-full font-semibold transition-colors duration-200">Request Demo</a>
            </div>
            <button class="md:hidden text-white text-2xl">&#9776;</button>
        </nav>
    </header>

    <main>
        <section class="hero bg-dark-gray text-white text-center py-20 px-4 md:py-32">
            <h1 class="text-4xl md:text-6xl font-black leading-tight mb-4">
                Automate. Optimize. Perfect. <br> The Future of Injection Molding is Here.
            </h1>
            <p class="text-lg md:text-xl text-gray-300 max-w-4xl mx-auto mb-8">
                Polycognition AI delivers a **closed-loop, lights-off system** leveraging advanced AI, Machine Learning, and Computer Vision to ensure **robust, defect-free, and in-spec molded parts** with unprecedented efficiency.
            </p>
            <div class="space-y-4 md:space-y-0 md:space-x-6 flex flex-col md:flex-row justify-center items-center">
                <a href="#contact" class="bg-primary hover:bg-[#5E35B1] text-white font-bold py-3 px-8 rounded-full text-lg shadow-lg transition-colors duration-300 w-full md:w-auto">
                    Request a Demo
                </a>
                <a href="#benefits" class="bg-transparent border-2 border-white hover:bg-white hover:text-dark-gray text-white font-bold py-3 px-8 rounded-full text-lg transition-colors duration-300 w-full md:w-auto">
                    Learn More
                </a>
            </div>
        </section>

        <section id="problem" class="py-16 px-4 md:px-8">
            <div class="container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-primary">The Costly Reality of Traditional Manufacturing</h2>
                <p class="text-center text-gray-700 max-w-3xl mx-auto mb-12">The injection molding industry is plagued by inefficiencies, high defect rates, and significant financial losses. These systemic issues demand an intelligent, automated solution.</p>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="stat-card border-secondary">
                        <p class="text-6xl md:text-7xl font-black text-secondary">$20B+</p>
                        <p class="mt-2 text-xl font-semibold">Lost Annually</p>
                        <p class="text-gray-600 mt-1 text-sm">Due to defective parts and wasted resources.</p>
                    </div>
                    <div class="stat-card border-primary">
                        <p class="text-6xl md:text-7xl font-black text-primary">12%</p>
                        <p class="mt-2 text-xl font-semibold">Average Scrap Rate</p>
                        <p class="text-gray-600 mt-1 text-sm">Significant portion of production failing quality checks.</p>
                    </div>
                    <div class="stat-card border-tertiary">
                        <p class="text-6xl md:text-7xl font-black text-tertiary">30%</p>
                        <p class="mt-2 text-xl font-semibold">Micro-Defects Missed</p>
                        <p class="text-gray-600 mt-1 text-sm">Unreliable manual inspections lead to downstream failures.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="solution" class="bg-gray-50 py-16 px-4 md:px-8">
            <div class="container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-primary">Introducing the Autonomous Injection Molding System</h2>
                <p class="text-center text-gray-700 max-w-4xl mx-auto mb-12">Polycognition AI revolutionizes manufacturing by integrating real-time data, intelligent decision-making, and robotic precision into a self-optimizing ecosystem.</p>
                
                <div class="flex flex-col md:flex-row justify-between items-stretch gap-6">
                    <div class="flow-step bg-white shadow-md border-b-4 border-primary">
                        <div class="icon-large text-primary">&#128269;</div>
                        <h3 class="text-xl font-bold mb-2">Sense & Analyze</h3>
                        <p class="text-gray-700 text-sm">IoT sensors collect thousands of data points per second. Computer vision scans every part with 99.98% accuracy.</p>
                    </div>
                    <div class="hidden md:flex items-center justify-center">
                        <span class="text-4xl text-primary font-bold">&rarr;</span>
                    </div>
                    <div class="flow-step bg-white shadow-md border-b-4 border-secondary">
                        <div class="icon-large text-secondary">&#129504;</div>
                        <h3 class="text-xl font-bold mb-2">Predict & Decide</h3>
                        <p class="text-gray-700 text-sm">Our core AI analyzes data, predicts potential defects up to 72 hours in advance, and determines optimal corrections.</p>
                    </div>
                    <div class="hidden md:flex items-center justify-center">
                        <span class="text-4xl text-primary font-bold">&rarr;</span>
                    </div>
                    <div class="flow-step bg-white shadow-md border-b-4 border-tertiary">
                        <div class="icon-large text-tertiary">&#9881;</div>
                        <h3 class="text-xl font-bold mb-2">Act & Optimize</h3>
                        <p class="text-gray-700 text-sm">The system autonomously adjusts machine parameters in milliseconds, correcting the process before a defect can form.</p>
                    </div>
                    <div class="hidden md:flex items-center justify-center">
                        <span class="text-4xl text-primary font-bold">&rarr;</span>
                    </div>
                    <div class="flow-step bg-white shadow-md border-b-4 border-accent">
                        <div class="icon-large text-accent">&#10004;</div>
                        <h3 class="text-xl font-bold mb-2">Perfect Output</h3>
                        <p class="text-gray-700 text-sm">The result: a continuous flow of robust, defect-free parts with near-zero waste and minimal human oversight.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="benefits" class="py-16 px-4 md:px-8">
            <div class="container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-primary">Unlocking Unprecedented ROI & Efficiency</h2>
                <p class="text-center text-gray-700 max-w-4xl mx-auto mb-12">Polycognition AI delivers quantifiable improvements across your entire injection molding operation, transforming your bottom line.</p>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6 border-b-4 border-primary hover:shadow-xl transition-shadow duration-300">
                        <div class="text-5xl text-primary mb-4 text-center">&#128337;</div>
                        <h3 class="text-2xl font-bold text-center mb-2">Up to 50%</h3>
                        <p class="text-gray-700 text-center">**Downtime Reduction** through predictive maintenance and autonomous adjustments.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-b-4 border-secondary hover:shadow-xl transition-shadow duration-300">
                        <div class="text-5xl text-secondary mb-4 text-center">&#128176;</div>
                        <h3 class="text-2xl font-bold text-center mb-2">Up to 40%</h3>
                        <p class="text-gray-700 text-center">**Maintenance Cost Savings** via proactive issue resolution and optimized machine health.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-b-4 border-accent hover:shadow-xl transition-shadow duration-300">
                        <div class="text-5xl text-accent mb-4 text-center">&#128465;&#65039;</div>
                        <h3 class="text-2xl font-bold text-center mb-2">Up to 40%</h3>
                        <p class="text-gray-700 text-center">**Scrap Rate Reduction** by preventing defects in real-time with 99.98% accurate quality control.</p>
                    </div>
                </div>
                 <div class="mt-12 text-center text-gray-700 max-w-3xl mx-auto">
                    <p class="text-xl font-semibold">Beyond these immediate savings, expect significant increases in production efficiency, enhanced product quality, and substantial labor cost reductions.</p>
                </div>
            </div>
        </section>

        <section id="technology" class="bg-gray-50 py-16 px-4 md:px-8">
            <div class="container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-primary">Our Core Technologies</h2>
                <p class="text-center text-gray-700 max-w-3xl mx-auto mb-12">Polycognition AI integrates a sophisticated stack of cutting-edge technologies to deliver truly autonomous manufacturing.</p>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center text-center">
                        <div class="icon-large text-primary">&#129504;</div>
                        <h3 class="text-xl font-bold mb-2">AI & Machine Learning</h3>
                        <p class="text-gray-700 text-sm">Adaptive algorithms continuously learn and optimize process parameters for defect prevention.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center text-center">
                        <div class="icon-large text-secondary">&#128269;</div>
                        <h3 class="text-xl font-bold mb-2">Computer Vision</h3>
                        <p class="text-gray-700 text-sm">High-speed, high-accuracy defect detection with deep learning, inspecting every single part.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center text-center">
                        <div class="icon-large text-tertiary">&#128736;&#65039;</div>
                        <h3 class="text-xl font-bold mb-2">Predictive Analytics</h3>
                        <p class="text-gray-700 text-sm">Forecasts equipment wear and potential failures up to 72 hours in advance for proactive maintenance.</p>
                    </p>
                    <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center text-center">
                        <div class="icon-large text-accent">&#129302;</div>
                        <h3 class="text-xl font-bold mb-2">Robotics Integration</h3>
                        <p class="text-gray-700 text-sm">Seamlessly integrates with industrial robots for lights-off material handling and operation.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center text-center">
                        <div class="icon-large text-primary">&#128187;</div>
                        <h3 class="text-xl font-bold mb-2">Digital Twin Ready</h3>
                        <p class="text-gray-700 text-sm">Foundation for virtual simulations and optimization of mold designs and production lines.</p>
                    </div>
                     <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center text-center">
                        <div class="icon-large text-secondary">&#128200;</div>
                        <h3 class="text-xl font-bold mb-2">Data-Driven Insights</h3>
                        <p class="text-gray-700 text-sm">Transforms raw production data into actionable intelligence for continuous improvement.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="market-sustainability" class="py-16 px-4 md:px-8">
            <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 text-primary">Massive Market, Sustainable Impact</h2>
                    <p class="text-gray-700 text-lg mb-4">We operate at the convergence of a **$190B+ injection molding industry** and a **rapidly growing AI in manufacturing market (46% CAGR)**, ensuring immense potential.</p>
                    <p class="text-gray-700 text-lg mb-6">Polycognition AI not only boosts profitability but also champions environmental responsibility:</p>
                    <ul class="list-none space-y-4 text-gray-700">
                        <li class="flex items-center text-lg">
                            <span class="text-accent text-3xl mr-3">&#128302;</span>
                            <span class="font-semibold">Reduced Material Waste:</span> Minimize scrap and raw material consumption.
                        </li>
                        <li class="flex items-center text-lg">
                            <span class="text-accent text-3xl mr-3">&#9889;</span>
                            <span class="font-semibold">Optimized Energy Use:</span> Intelligent systems cut energy footprint.
                        </li>
                        <li class="flex items-center text-lg">
                            <span class="text-accent text-3xl mr-3">&#127757;</span>
                            <span class="font-semibold">Circular Economy Support:</span> Better manages recycled materials for higher quality output.
                        </li>
                    </ul>
                </div>
                <div class="relative bg-white rounded-lg shadow-xl p-8">
                    <img src="https://placehold.co/600x400/6D47D9/ffffff?text=Industrial+AI+Vision" alt="AI in Manufacturing" class="rounded-lg mb-4">
                    <p class="text-gray-600 text-sm text-center">Polycognition AI integrates seamless AI vision with machine control to achieve a new level of manufacturing autonomy.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="bg-dark-gray text-white py-16 px-4 md:px-8 text-center">
            <div class="container mx-auto max-w-3xl">
                <h2 class="text-3xl md:text-4xl font-bold mb-6 text-primary">Ready to Transform Your Manufacturing?</h2>
                <p class="text-gray-300 text-xl mb-8">Schedule a personalized consultation and discover how Polycognition AI can deliver defect-free, lights-off production for your business.</p>
                <a href="mailto:invest@polycognition.ai" class="bg-secondary hover:bg-[#D8366D] text-white font-bold py-4 px-10 rounded-full text-xl shadow-lg transition-colors duration-300 inline-block">
                    Schedule a Consultation
                </a>
            </div>
        </section>
    </main>

    <footer class="bg-dark-gray text-gray-400 py-6 px-4 md:px-8 text-center text-sm">
        <div class="container mx-auto">
            <p>&copy; 2025 Polycognition AI. All Rights Reserved.</p>
            <p class="mt-2">Redefining Precision Manufacturing through Artificial Intelligence.</p>
        </div>
    </footer>

</body>
</html>
```
