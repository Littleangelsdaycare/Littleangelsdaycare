<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Angels Daycare School Rules & Regulations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f8f9fa;
        }
        .container {
            max-width: 700px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            background: #007bff;
            color: white;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
            font-weight: bold;
            text-transform: uppercase;
        }
        .content {
            display: none;
            padding: 10px;
            background: #e9ecef;
            border-radius: 5px;
            margin-top: 5px;
        }
        .highlight {
            color: red;
            font-weight: bold;
        }
        img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Little Angels Daycare School Rules & Regulations</h2>
        <img src="school_rules.jpg" alt="School Rules">
        
        <div class="section" onclick="toggleContent('students')">Students</div>
        <div id="students" class="content">
            <ul>
                <li><span class="highlight">1.</span> All students must arrive at school by <span class="highlight">8:45 a.m.</span></li>
                <li><span class="highlight">2.</span> Classes will commence at <span class="highlight">9:00 a.m.</span></li>
                <li><span class="highlight">3.</span> Students must bring their own <span class="highlight">tiffin and drinking water</span> daily.</li>
                <li><span class="highlight">4.</span> Students suffering from <span class="highlight">contagious diseases</span> are not permitted to attend classes until fully recovered.</li>
                <li><span class="highlight">5.</span> Participation in <span class="highlight">co-curricular and non-academic activities</span> is mandatory.</li>
                <li><span class="highlight">6.</span> Students must wear the <span class="highlight">school uniform and identity card</span> every day.</li>
            </ul>
        </div>
        
        <div class="section" onclick="toggleContent('parents')">Parents</div>
        <div id="parents" class="content">
            <ul>
                <li><span class="highlight">1.</span> Parents should discuss their child’s concerns, including <span class="highlight">health issues</span>, with the school for better care and support.</li>
                <li><span class="highlight">2.</span> Official school information will be communicated via the <span class="highlight">designated school information group</span>.</li>
                <li><span class="highlight">3.</span> Birthday celebrations are allowed, but <span class="highlight">cakes and colorful attire</span> are not permitted.</li>
                <li><span class="highlight">4.</span> Parents must <span class="highlight">label all their child’s belongings</span>, including books and other personal items.</li>
                <li><span class="highlight">5.</span> If a student is absent for more than three days or during exams, a <span class="highlight">medical certificate</span> must be submitted.</li>
                <li><span class="highlight">6.</span> Phone calls regarding <span class="highlight">drop-off and pick-up</span> are only allowed in emergencies.</li>
            </ul>
        </div>
        
        <div class="section" onclick="toggleContent('teachers')">Teachers</div>
        <div id="teachers" class="content">
            <ul>
                <li><span class="highlight">1.</span> Teachers must report to school by <span class="highlight">8:30 a.m.</span> and stay until <span class="highlight">1:00 p.m.</span></li>
                <li><span class="highlight">2.</span> <span class="highlight">Private tuition</span> within school premises is strictly prohibited.</li>
                <li><span class="highlight">3.</span> <span class="highlight">T-shirts without collars</span> are not allowed.</li>
                <li><span class="highlight">4.</span> <span class="highlight">Ice-breaking and vocabulary activities</span> (15-20 min) are mandatory for active learning.</li>
            </ul>
        </div>
    </div>
    
    <script>
        function toggleContent(id) {
            var content = document.getElementById(id);
            if (content.style.display === "block") {
                content.style.display = "none";
            } else {
                content.style.display = "block";
            }
        }
    </script>
</body>
</html>
