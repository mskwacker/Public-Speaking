# Public-Speaking
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Public Speaking Jeopardy</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f0f8ff;
    }
    table {
      margin: auto;
      border-collapse: collapse;
      width: 90%;
    }
    th, td {
      border: 2px solid #000;
      padding: 20px;
      font-size: 1.2em;
      background-color: #1e90ff;
      color: white;
      cursor: pointer;
    }
    td.revealed {
      background-color: #fff;
      color: #000;
    }
  </style>
</head>
<body>
  <h1>Public Speaking Jeopardy</h1>
  <table>
    <thead>
      <tr>
        <th>Speech Purposes</th>
        <th>Communication</th>
        <th>Ethics</th>
        <th>Speech Writing</th>
        <th>Delivery</th>
        <th>Rhetorical Situation</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td onclick="reveal(this, 'What are the three general purposes of a speech?')">100</td>
        <td onclick="reveal(this, 'Name the four parts of the communication cycle.')">100</td>
        <td onclick="reveal(this, 'What gives us the civic right to speak publicly?')">100</td>
        <td onclick="reveal(this, 'List two types of hook techniques.')">100</td>
        <td onclick="reveal(this, 'List three traits of strong body language during a speech.')">100</td>
        <td onclick="reveal(this, 'What are the five parts of the rhetorical situation?')">100</td>
      </tr>
      <tr>
        <td onclick="reveal(this, 'What is the difference between a thesis and a preview?')">200</td>
        <td onclick="reveal(this, 'List two traits of effective listening.')">200</td>
        <td onclick="reveal(this, 'What is plagiarism?')">200</td>
        <td onclick="reveal(this, 'What belongs in the conclusion of a speech?')">200</td>
        <td onclick="reveal(this, 'What is articulation?')">200</td>
        <td onclick="reveal(this, 'What does macrostructure refer to in a speech outline?')">200</td>
      </tr>
      <tr>
        <td onclick="reveal(this, 'What are the three main parts of a speech outline?')">300</td>
        <td onclick="reveal(this, 'What is incongruent communication?')">300</td>
        <td onclick="reveal(this, 'Name one trait of an ethical communicator.')">300</td>
        <td onclick="reveal(this, 'How long should one main point be (in words)?')">300</td>
        <td onclick="reveal(this, 'Name two vocal delivery techniques.')">300</td>
        <td onclick="reveal(this, 'What does microstructure include?')">300</td>
      </tr>
    </tbody>
  </table>
  <script>
    function reveal(cell, question) {
      cell.classList.add('revealed');
      cell.innerHTML = question;
    }
  </script>
</body>
</html>
