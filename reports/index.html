<!DOCTYPE html>
<html>
<head>
  <title>Health Buddy Reports</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    h1 { color: #333; }
    ul { list-style-type: none; padding: 0; }
    li { margin: 10px 0; }
    a { text-decoration: none; color: #0066cc; }
    a:hover { text-decoration: underline; }
  </style>
</head>
<body>
  <h1>Reports</h1>
  <p>Browse all report categories and files below:</p>
  <ul id="report-list"></ul>
  <p><a href="../">Back to Home</a></p>

  <script>
    // Replace with your repo details
    const repoUrl = "https://api.github.com/repos/ypff/health_buddy_reports_new/contents/reports";
    const baseUrl = "https://ypff.github.io/health_buddy_reports_new/reports/";

    fetch(repoUrl)
      .then(response => response.json())
      .then(data => {
        const reportList = document.getElementById("report-list");
        data.forEach(item => {
          // Create a list item for each folder or file
          const li = document.createElement("li");
          const a = document.createElement("a");
          a.href = baseUrl + item.name;
          a.textContent = item.name;
          li.appendChild(a);
          reportList.appendChild(li);

          // If it's a folder, fetch its contents
          if (item.type === "dir") {
            fetch(item.url)
              .then(res => res.json())
              .then(files => {
                const ul = document.createElement("ul");
                files.forEach(file => {
                  const fileLi = document.createElement("li");
                  const fileA = document.createElement("a");
                  fileA.href = baseUrl + item.name + "/" + file.name;
                  fileA.textContent = file.name;
                  fileLi.appendChild(fileA);
                  ul.appendChild(fileLi);
                });
                li.appendChild(ul);
              });
          }
        });
      })
      .catch(error => console.error("Error fetching repo contents:", error));
  </script>
</body>
</html>
