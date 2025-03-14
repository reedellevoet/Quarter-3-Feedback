# Quarter-3-Feedback
Let me know your general feedback from Quarter 3 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quarter 3 Reflection & Feedback</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 600px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: auto;
        }
        label {
            font-weight: bold;
        }
        textarea, input, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background: #28a745;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Quarter 3 Reflection & Feedback</h2>
        <p>Please take a few minutes to answer these questions honestly. Your feedback helps make our class better!</p>
        
        <form action="#" method="POST">
            <label>If you could time travel to any year, past or future, where would you go and why?</label>
            <textarea name="time_travel" required></textarea>
            
            <label>If last quarter was a movie, what would its title be?</label>
            <input type="text" name="movie_title" required>
            
            <label>Would you rather always show your work in math or never use a calculator again?</label>
            <select name="math_preference">
                <option value="show_work">Always show my work</option>
                <option value="no_calculator">Never use a calculator again</option>
            </select>
            
            <label>What did you like about last quarter in this classroom?</label>
            <textarea name="like_classroom" required></textarea>
            
            <label>What did you not like about last quarter?</label>
            <textarea name="dislike_classroom" required></textarea>
            
            <label>If you could change one thing about this class, what would it be?</label>
            <textarea name="change_classroom" required></textarea>
            
            <label>What are some things I did well as a teacher?</label>
            <textarea name="teacher_good" required></textarea>
            
            <label>What are some things you think I could improve on?</label>
            <textarea name="teacher_improve" required></textarea>
            
            <label>What is one specific goal you have for yourself for the final quarter of middle school?</label>
            <textarea name="student_goal" required></textarea>
            
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
