---
permalink: /teaching/teaching-evaluations
---

<p style = "font-size: 1.563em; font-weight: bold">Teaching Evaluations</p>


<style>
body {
  padding: 20px;
}

/* Bar Graph Horizontal */
.bar-graph .year {
  -webkit-animation: fade-in-text 2.2s 0.1s forwards;
  -moz-animation: fade-in-text 2.2s 0.1s forwards;
  animation: fade-in-text 2.2s 0.1s forwards;
  opacity: 0;
}

.bar-graph-horizontal {
  max-width: 380px;
}

.bar-graph-horizontal > div {
  float: left;
  margin-bottom: 8px;
  width: 100%;
}

.bar-graph-horizontal .year {
  float: left;
  margin-top: 18px;
  width: 50px;
}

.bar-graph-horizontal .bar {
  border-radius: 3px;
  height: 55px;
  float: left;
  overflow: hidden;
  position: relative;
  width: 0;
}

.bar-graph-one .bar::after {
  -webkit-animation: fade-in-text 2.2s 0.1s forwards;
  -moz-animation: fade-in-text 2.2s 0.1s forwards;
  animation: fade-in-text 2.2s 0.1s forwards;
  color: #fff;
  content: attr(data-percentage);
  font-weight: 700;
  position: absolute;
  right: 16px;
  top: 17px;
}

.bar-graph-one .bar-one .bar {
  background-color: #64b2d1;
  -webkit-animation: show-bar-one 1.2s 0.1s forwards;
  -moz-animation: show-bar-one 1.2s 0.1s forwards;
  animation: show-bar-one 1.2s 0.1s forwards;
}

.bar-graph-one .bar-two .bar {
  background-color: #5292ac;
  -webkit-animation: show-bar-two 1.2s 0.2s forwards;
  -moz-animation: show-bar-two 1.2s 0.2s forwards;
  animation: show-bar-two 1.2s 0.2s forwards;
}

.bar-graph-one .bar-three .bar {
  background-color: #407286;
  -webkit-animation: show-bar-three 1.2s 0.3s forwards;
  -moz-animation: show-bar-three 1.2s 0.3s forwards;
  animation: show-bar-three 1.2s 0.3s forwards;
}

.bar-graph-one .bar-four .bar {
  background-color: #2e515f;
  -webkit-animation: show-bar-four 1.2s 0.4s forwards;
  -moz-animation: show-bar-four 1.2s 0.4s forwards;
  animation: show-bar-four 1.2s 0.4s forwards;
}

/* Bar Graph Horizontal Animations */
@-webkit-keyframes show-bar-one {
  0% {
    width: 0;
  }
  100% {
    width: 69.6%;
  }
}

@-webkit-keyframes show-bar-two {
  0% {
    width: 0;
  }
  100% {
    width: 71%;
  }
}

@-webkit-keyframes show-bar-three {
  0% {
    width: 0;
  }
  100% {
    width: 74.7%;
  }
}

@-webkit-keyframes show-bar-four {
  0% {
    width: 0;
  }
  100% {
    width: 76.8%;
  }
}

@-webkit-keyframes fade-in-text {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

    </style>

<head>
    <title>Support from the instructor</title>
    <style>
        /* CSS for styling the dropdown */
        #dropdownContainer {
            position: relative;
            display: inline-block;
        }

        #openButton {
            padding: 10px 20px;
            background-color: #3498db;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        #graphDropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #fff;
            border: 1px solid #ccc;
        }

        .chart {
            width: 400px;
            height: 300px;
            border: 1px solid #ccc;
            margin: 10px;
        }

        .bar {
            width: 100px;
            height: 20px;
            background-color: #3498db;
            margin-bottom: 10px;
            position: relative;
        }

        .label {
            font-size: 14px;
            margin-top: 5px;
        }

        .bar-label {
            position: absolute;
            left: 0;
            top: 0;
            height: 100%;
            width: 40px;
            text-align: right;
            line-height: 20px;
            color: #fff;
            padding-right: 10px;
        }
    </style>
</head>
<body>
    <div id="dropdownContainer">
        <button id="openButton" onclick="toggleDropdown()">Open Bar Graph</button>
        <div id="graphDropdown">
            <div class="chart">
                <section class="bar-graph bar-graph-horizontal bar-graph-one">
  <div class="bar-one">
    <span class="year">2019</span>
    <div class="bar" data-percentage="300%"></div>
  </div>
  <div class="bar-two">
    <span class="year">2018</span>
    <div class="bar" data-percentage="71%"></div>
  </div>
  <div class="bar-three">
    <span class="year">2017</span>
    <div class="bar" data-percentage="74.7%"></div>
  </div>
</section>


            </div>
        </div>
    </div>

    <script>
        // JavaScript code to toggle the dropdown visibility
        function toggleDropdown() {
            const graphDropdown = document.getElementById('graphDropdown');
            graphDropdown.style.display = (graphDropdown.style.display === 'block') ? 'none' : 'block';
        }
    </script>
</body>


