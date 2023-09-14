---
permalink: /teaching/teaching-evaluations
---

<p style = "font-size: 1.563em; font-weight: bold">Teaching Evaluations</p>

<head>
    <title>Horizontal Bar Graph with Button</title>
    <style>
        /* CSS for styling the horizontal bar graph */
        .graph-container {
            position: relative;
            width: 400px;
            height: 300px;
            border: 1px solid #ccc;
            margin: 20px auto;
        }

        .bar {
            position: absolute;
            height: 20px;
            background-color: #3498db;
            transition: width 0.5s;
        }

        .y-axis-label {
            position: absolute;
            top: 10px;
            left: -40px;
            text-align: right;
        }

        .x-axis-label {
            text-align: center;
            margin-top: 10px;
        }

        /* CSS for styling the button */
        .graph-button {
            display: block;
            margin: 10px auto;
            padding: 10px 20px;
            background-color: #3498db;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <button class="graph-button" onclick="toggleGraph()">Toggle Graph</button>

    <div class="graph-container" style="display: none;">
        <!-- Bars -->
        <div class="bar" style="width: 100px; bottom: 10px;"></div>
        <div class="bar" style="width: 150px; bottom: 40px;"></div>
        <div class="bar" style="width: 80px; bottom: 70px;"></div>
        <div class="bar" style="width: 120px; bottom: 100px;"></div>
        <div class="bar" style="width: 200px; bottom: 130px;"></div>

        <!-- Y-axis labels -->
        <div class="y-axis-label">Label 1</div>
        <div class="y-axis-label">Label 2</div>
        <div class="y-axis-label">Label 3</div>
        <div class="y-axis-label">Label 4</div>
        <div class="y-axis-label">Label 5</div>

        <!-- X-axis label -->
        <div class="x-axis-label">X-axis</div>
    </div>

    <script>
        // JavaScript code for button functionality
        function toggleGraph() {
            const graphContainer = document.querySelector('.graph-container');
            graphContainer.style.display = graphContainer.style.display === 'none' ? 'block' : 'none';
        }
    </script>
</body>
