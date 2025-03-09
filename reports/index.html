<!DOCTYPE html>
<html>
<head>
  <title>Health Buddy Reports - Reports</title>
  <style>
    body {
      font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
      background-color: #2b2b2b;
      color: #d3d3d3;
      margin: 40px;
      line-height: 1.6;
    }
    h1 {
      color: #ffffff;
      font-size: 2em;
      border-bottom: 2px solid #d3d3d3;
      padding-bottom: 10px;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin: 15px 0;
    }
    a {
      color: #88ccff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
      color: #ffffff;
    }
    p {
      color: #bbbbbb;
    }
    .subfolder {
      margin-left: 20px;
    }
  </style>
</head>
<body>
  <h1>Reports</h1>
  <p>Browse all reports below:</p>
  <ul id="report-list"></ul>
  <p><a href="../">Back to Home</a></p>

  <script>
    const repoUrl = "https://api.github.com/repos/ypff/health_buddy_reports_new/contents/reports";
    const baseUrl = "https://ypff.github.io/health_buddy_reports_new/reports/";

    fetch(repoUrl)
      .then(response => response.json())
      .then(data => {
        const reportList = document.getElementById("report-list");
        data.forEach(item => {
          if (item.name !== "index.html") {  // Hide index.html
            const li = document.createElement("li");
            const a = document.createElement("a");
            a.href = baseUrl + item.name;
            a.textContent = item.name;
            li.appendChild(a);
            reportList.appendChild(li);

            if (item.type === "dir") {
              fetch(item.url)
                .then(res => res.json())
                .then(files => {
                  const ul = document.createElement("ul");
                  ul.className = "subfolder";
                  files.forEach(file => {
                    if (file.name !== "index.html") {  // Hide index.html in subfolders
                      const fileLi = document.createElement("li");
                      const fileA = document.createElement("a");
                      fileA.href = baseUrl + item.name + "/" + file.name;
                      fileA.textContent = file.name;
                      fileLi.appendChild(fileA);
                      ul.appendChild(fileLi);
                    }
                  });
                  if (ul.children.length > 0) li.appendChild(ul);
                });
            }
          }
        });
      })
      .catch(error => console.error("Error fetching repo contents:", error));
  </script>
</body>
</html>
