---
layout: default
title: Sima Didari - AI Research
---

<div class="header">
    <div class="profile-section">
        <img src="assets/images/profile.jpg" alt="Sima Didari" class="profile-image" onerror="this.style.display='none'">
        <div class="profile-info">
            <h1>Sima Didari</h1>
            <div class="profile-summary">
                <p>Welcome to my research portfolio. I am a Senior Staff AI Scientist with 10+ years of experience in Deep Learning, Computer Vision, Bayesian Machine Learning, Generative AI, and Large Language Models. My work focuses on developing foundational AI technologies and translating cutting-edge research into real-world applications that create significant impact across industries.</p>
                
                <p>For more detailed explanations of my research interests and current projects, please explore the research area tabs below.</p>
            </div>
        </div>
    </div>
    
    <div class="contact-info">
        <a href="mailto:Sima.Didari@gmail.com" class="contact-item">Sima.Didari@gmail.com</a>
        <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID" class="contact-item" target="_blank">Google Scholar</a>
        <a href="https://linkedin.com/in/simadidari" class="contact-item" target="_blank">LinkedIn</a>
        <span class="contact-item">Samsung SDS AI Science Lab</span>
    </div>
</div>



<div class="content-section">
    <h2>Recent Publications</h2>
    <p style="margin-bottom: 20px;">For a complete list of publications and citations, please visit my <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID" target="_blank">Google Scholar profile</a>.</p>
    
    <div class="publication-item">
        <strong>Improving instruction following in language models through proxy-based uncertainty estimation</strong><br>
        <em>International Conference on Machine Learning (ICML), 2024</em><br>
        <p style="margin-top: 10px; color: #666; font-size: 0.95em;">Novel uncertainty-aware reward model that significantly improves LLM alignment with reduced human feedback requirements. Demonstrates substantial improvements on Vicuna and MT-bench evaluations.</p>
    </div>
    
    <div class="publication-item">
        <strong>Bayesian active learning for semantic segmentation</strong><br>
        <em>arXiv:2408.01694, 2024</em><br>
        <p style="margin-top: 10px; color: #666; font-size: 0.95em;">Introduces Beta distribution approximation for efficient uncertainty estimation in semantic segmentation, achieving significant annotation cost reductions.</p>
    </div>
    
    <div class="publication-item">
        <strong>Self-Supervised contrastive representation learning for 3D mesh segmentation</strong><br>
        <em>arXiv:2208.04278, 2022</em><br>
        <p style="margin-top: 10px; color: #666; font-size: 0.95em;">Pioneering self-supervised approach for 3D geometric data analysis, eliminating the need for manual annotations in mesh segmentation tasks.</p>
    </div>
    
    <div class="publication-item">
        <strong>Active learning performance in labeling radiology images is 90% Effective</strong><br>
        <em>Frontiers in Radiology, 2021</em><br>
        <p style="margin-top: 10px; color: #666; font-size: 0.95em;">Clinical validation demonstrating dramatic reduction in radiologist annotation burden while maintaining diagnostic accuracy.</p>
    </div>
    
    <div class="publication-item">
        <strong>Modeling and optimizing process parameters in sputtering systems using Gaussian processes</strong><br>
        <em>IEEE Transactions on Semiconductor Manufacturing, 2021</em><br>
        <p style="margin-top: 10px; color: #666; font-size: 0.95em;">Industrial application of Bayesian optimization resulting in significant yield improvements and cost reductions in semiconductor manufacturing.</p>
    </div>
</div>



<div class="content-section">
    <h2>Research Interests</h2>
    
    <p style="margin-bottom: 30px;">My research is driven by the principle that AI should be both theoretically grounded and practically impactful. I focus on developing methods that not only advance the state-of-the-art but also address real-world challenges in industry and society.</p>
    
    <div class="research-tabs">
        <div class="tabs-header">
            <button class="tab-button" onclick="showTab('genai', this)">Generative AI & LLMs</button>
            <button class="tab-button" onclick="showTab('computer-vision', this)">Computer Vision</button>
            <button class="tab-button" onclick="showTab('optimization', this)">Optimization & ML</button>
        </div>
        
        <div id="genai" class="tab-content">
            <div style="margin: 40px 0;">
                <h3>Generative AI & Large Language Models</h3>
                <p style="font-size: 1em; color: #666; margin-bottom: 20px;">My work in generative AI focuses on developing more reliable and efficient language models through novel uncertainty quantification methods and data-efficient alignment techniques. I am particularly interested in creating multimodal systems that can seamlessly integrate text, image, and structured data to solve complex real-world problems.</p>
                
                <h4>Current Research Focus</h4>
                <ul style="margin-bottom: 20px;">
                    <li>Data-efficient alignment techniques and fine-tuning for large language models</li>
                    <li>Proxy-based uncertainty estimation for improving instruction following</li>
                    <li>Retrieval-Augmented Generation (RAG) systems for knowledge-intensive tasks</li>
                    <li>Text-to-SQL generation and automated coding assistance</li>
                    <li>Graph learning approaches for RL alignment and structured reasoning</li>
                    <li>Multimodal LLMs for text, image, and tabular data integration</li>
                </ul>
                
                <a href="genai.html" style="color: #333; border: 1px solid #ccc; padding: 10px 20px; text-decoration: none;">Explore Research →</a>
            </div>
        </div>
        
        <div id="computer-vision" class="tab-content">
            <div style="margin: 40px 0;">
                <h3>Computer Vision & Deep Learning</h3>
                <p style="font-size: 1em; color: #666; margin-bottom: 20px;">My computer vision research centers on developing intelligent systems that can learn effectively with minimal supervision while providing reliable uncertainty estimates. I focus on active learning frameworks and self-supervised methods that dramatically reduce annotation costs while maintaining high performance, particularly for medical and industrial applications.</p>
                
                <h4>Research Contributions</h4>
                <ul style="margin-bottom: 20px;">
                    <li>Bayesian active learning frameworks for semantic segmentation</li>
                    <li>Self-supervised representation learning for 3D mesh analysis</li>
                    <li>Uncertainty-aware computer vision for medical imaging</li>
                    <li>Multi-view 3D semantic segmentation systems</li>
                </ul>
                
                <a href="computer-vision.html" style="color: #333; border: 1px solid #ccc; padding: 10px 20px; text-decoration: none;">Explore Research →</a>
            </div>
        </div>
        
        <div id="optimization" class="tab-content">
            <div style="margin: 40px 0;">
                <h3>Optimization & Machine Learning</h3>
                <p style="font-size: 1em; color: #666; margin-bottom: 20px;">My optimization research bridges mathematical optimization theory with practical machine learning applications, focusing on Bayesian methods that provide principled uncertainty quantification. I develop frameworks that enable robust, efficient decision-making in complex engineering and business environments where understanding uncertainty is critical for safe and effective AI deployment.</p>
                
                <h4>Key Methodologies</h4>
                <ul style="margin-bottom: 20px;">
                    <li>Gaussian Process frameworks for process optimization</li>
                    <li>Bayesian optimization for hyperparameter tuning and design</li>
                    <li>Uncertainty quantification in complex engineering systems</li>
                    <li>Predictive analytics for industrial applications</li>
                </ul>
                
                <a href="optimization.html" style="color: #333; border: 1px solid #ccc; padding: 10px 20px; text-decoration: none;">Explore Research →</a>
            </div>
        </div>
    </div>
    
    <h4 style="margin-top: 40px;">Core Research Themes:</h4>
    <ul>
        <li><strong>Uncertainty-Aware AI:</strong> Developing methods that quantify and leverage uncertainty for more reliable AI systems</li>
        <li><strong>Data Efficiency:</strong> Creating learning algorithms that achieve superior performance with minimal labeled data</li>
        <li><strong>Industrial Translation:</strong> Bridging the gap between research innovations and practical industrial applications</li>
        <li><strong>Human-AI Collaboration:</strong> Designing systems that effectively combine human expertise with AI capabilities</li>
    </ul>
    
    <h4>Current Collaborations:</h4>
    <p style="margin-top: 15px;">Active collaborations with academic institutions and industry partners, including work with MIT on advanced manufacturing optimization and cross-functional teams at Samsung for next-generation AI products.</p>
</div>

<div class="content-section">
    <h2>Professional Background</h2>
    
    <div class="timeline-item">
        <div class="timeline-date">2019 – Present</div>
        <div class="timeline-title">Senior Staff AI Scientist</div>
        <div class="timeline-company">Samsung SDS AI Science Lab | San Jose, CA</div>
        <p>Leading research initiatives in generative AI, computer vision, and optimization. Responsible for developing breakthrough technologies that secure Samsung's competitive advantages in AI-driven solutions.</p>
    </div>
    
    <div class="timeline-item">
        <div class="timeline-date">2017 – 2019</div>
        <div class="timeline-title">Senior Data Scientist</div>
        <div class="timeline-company">Applied Materials | Santa Clara, CA</div>
        <p>Pioneered AI applications in semiconductor manufacturing, including real-time anomaly detection and predictive maintenance systems.</p>
    </div>
    
    <div class="timeline-item">
        <div class="timeline-date">2014 – 2017</div>
        <div class="timeline-title">Research Engineer</div>
        <div class="timeline-company">GE Global Research | San Ramon, CA & Niskayuna, NY</div>
        <p>Developed probabilistic machine learning methods for industrial applications, contributing to GE's core AI infrastructure and uncertainty quantification capabilities.</p>
    </div>
    
    <div class="timeline-item">
        <div class="timeline-date">Ph.D. 2014</div>
        <div class="timeline-title">Mechanical Engineering</div>
        <div class="timeline-company">Georgia Institute of Technology | Atlanta, GA</div>
        <p>Doctoral research in computational optimization and materials science, focusing on topological optimization of 3D composite structures.</p>
    </div>
</div>