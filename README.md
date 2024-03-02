<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Without Semantic HTML</title>
</head>
<body>
    <h1>Form Without Semantic HTML</h1>
    <form>
        <section>
            <label for="fullName">Full Name:</label>
            <input type="text" id="fullName" name="fullName" required>
        </section>
        
        <section>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </section>

        <section>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
        </section>
        
        <section>
            <label for="gender">Gender:</label>
            <select name="gender" id="gender">
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        </section>

        <section>
            <label>
                <input type="checkbox" id="newsletter" name="newsletter">Subscribe to Newesletter:
            </label>
        </section>

        <section>
            <label for="comments">Comments:</label>
            <textarea name="comments" id="comments" rows="4"></textarea>
        </section>
       
        <button type="submit">Submit</button>
    </form>
</body>
</html>