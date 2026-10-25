# Assignment 4.2 — Job Application Form

**File name: `job-application.html`**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Job Application Form</title>
</head>
<body>
    <h1>Job Application Form</h1>

    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone" required><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <label for="portfolio">Portfolio URL:</label>
        <input type="url" id="portfolio" name="portfolio"><br><br>

        <p>Preferred Shift:</p>
        <input type="radio" id="day" name="shift" value="day">
        <label for="day">Day</label>
        <input type="radio" id="night" name="shift" value="night">
        <label for="night">Night</label><br><br>

        <p>Skills:</p>
        <input type="checkbox" id="html" name="skills" value="HTML">
        <label for="html">HTML</label>
        <input type="checkbox" id="css" name="skills" value="CSS">
        <label for="css">CSS</label>
        <input type="checkbox" id="js" name="skills" value="JavaScript">
        <label for="js">JavaScript</label><br><br>

        <label for="qualification">Qualification:</label>
        <select id="qualification" name="qualification" required>
            <option value="">Select</option>
            <option value="12th">12th Pass</option>
            <option value="btech">B.Tech</option>
            <option value="graduate">Graduate</option>
        </select><br><br>

        <label for="letter">Cover Letter:</label><br>
        <textarea id="letter" name="cover-letter" rows="4"></textarea><br><br>

        <label for="jobid">Job ID:</label>
        <input type="text" id="jobid" value="JOB101" disabled><br><br>

        <button type="submit">Apply Now</button>
    </form>
</body>
</html>
```

**Submission:** Save as `job-application.html`, open it in a browser, and submit the HTML file with a screenshot.