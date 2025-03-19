# Dream-Team_Okakichi

Assessment for Full-Stack/Backend Developer

Introduction
This document outlines a comprehensive assessment process for evaluating candidates applying for full-stack or backend developer positions. The assessment includes sections on personality, common sense, logical reasoning, troubleshooting, and coding skills.

Personality Test

How do you handle a situation where you disagree with a team member's idea?</br>
I would speak up and share openly my idea and tell the reason why I disagree with their idea and open to discussion.

What motivates you to work on a project?</br>
I’m happy to take on a new challenge, what motivates me as a developer is to see my application or project successfully delivered and being used by the end user. That will give me satisfaction as a developer.

How do you manage stress during tight deadlines?</br>
I would break the task into smaller, manageable steps and focus on completing them one at a time. This approach helps me stay motivated and prevents feeling overwhelmed. As I make progress, I often find that the larger task naturally comes together, which keeps me focused and reduces stress.

How do you prioritize tasks when working on multiple projects simultaneously?</br>
I’ll prioritize tasks based on urgency and complexity. I’ll start by tackling the most time-sensitive or challenging tasks first, as they often require the most focus and effort. At the same time, I ensure that simpler tasks are also progressing, so nothing falls behind. This approach helps me stay organized and meet all deadlines effectively.

Can you describe a situation where you had to adapt to a new technology or process? How did you handle it?</br>
I recognized that adapting to the new technology was essential for staying competitive and efficient. I approached the change with curiosity and a willingness to learn, rather than resistance. To handle this, I work closely with teammates who are also learning the tool. Shared tips, troubleshooted issues together, and developed best practices as a group. I’ll create a dummy project to test the tool's features and explore its capabilities.

How do you handle constructive criticism or feedback on your work?</br>
I welcome constructive criticism and feedback because it helps me grow and improve. When I receive feedback, I listen carefully to understand the perspective being shared and take it as an opportunity to learn. I then reflect on the input and make the necessary adjustments to my work. This approach not only helps me correct mistakes but also ensures continuous improvement in my performance.

What do you value most in a work environment?</br>
In a work environment, I value having supportive teammates, strong leadership, and a healthy work-life balance. I also appreciate an open and collaborative culture where I feel comfortable sharing my ideas and feedback. These elements create a positive and productive atmosphere that helps me thrive both personally and professionally.


Common Sense Test

If you were tasked with organizing a team-building event but realized you had forgotten to book the venue, what would you do?</br>
I would first stay calm and assess the situation. I would immediately check the availability of the original venue and, if it’s fully booked, quickly research and secure an alternative option. I would also inform my supervisor about the issue and keep them updated on the steps I’m taking to resolve it. If the situation cannot be resolved as planned, I would take responsibility, apologize to the team, and work on finding a suitable solution to ensure the event can still proceed successfully.

How would you handle a situation where a colleague is consistently late to meetings?</br>
I would address the situation professionally and respectfully. I would privately speak with them to understand if there are any underlying reasons for their tardiness, such as conflicting priorities or personal challenges. Based on their response, I would offer support or suggest solutions, such as adjusting meeting times or setting reminders. If the issue persists, I would involve a supervisor or manager to help find a resolution while maintaining a positive and collaborative approach.

If you noticed a mistake in a document that was about to be sent to a client, what would you do?</br>
I would immediately inform the relevant team members and work quickly to correct the error. I would double-check the entire document to ensure there are no additional issues and confirm the changes with the team before finalizing it. My priority would be to maintain accuracy and professionalism while meeting the deadline.

If you were tasked with organizing a team event but realized you forgot to send out invitations, what would you do?</br>
I would send out the invitations immediately, apologize for the delay, and provide clear details about the event. To ensure maximum attendance, I would follow up with reminders and personally reach out to key team members. Additionally, I would review my process to prevent similar oversights in the future.

How would you handle a situation where a colleague is struggling with their workload?</br>
I would first approach them to offer my support and ask how I can assist. I would listen to their concerns and, if appropriate, suggest collaborating to prioritize tasks or redistribute responsibilities. If the issue is beyond my capacity to help, I would encourage them to discuss the situation with a manager or supervisor to ensure they receive the necessary support. 

How would you handle a situation where a project's timeline is at risk due to unforeseen delays?</br>
I would immediately gather the team to identify the root cause of the issue. Together, we would assess the impact on the timeline and brainstorm solutions to address the bottleneck. Depending on the situation, we might reallocate resources, adjust priorities, or negotiate an updated timeline with stakeholders. My focus would be on clear communication, teamwork, and finding practical solutions to keep the project on track.


Troubleshooting Test

A user reports that a game crashes when they try to load a specific level. How would you troubleshoot this issue?</br>
I would first replicate the issue to confirm the problem. Then, I would debug the level by checking for errors in the code, assets, or dependencies that might cause the crash. I would review logs, memory usage, and any recent changes to the level. Once I identify the root cause, I would fix the issue, test the solution thoroughly, and deploy the update. Finally, I would follow up with the user to ensure the problem is resolved and document the issue for future reference.

If a web application is slow to load, what steps would you take to improve its performance?</br>
I would first identify the root cause by analyzing potential factors such as server load, database performance, query execution, or network latency. I would use tools like performance monitoring software, logs, and profiling to pinpoint the issue. Once the cause is identified, I would take targeted actions to resolve it. For example, if the slowness is due to inefficient queries, I would optimize them. If it’s related to server load, I might scale resources or implement caching. After implementing the fix, I would test the application to ensure performance improvements and monitor it to prevent future issues.

Suppose a database query is taking too long to execute. How would you optimize it?</br>
I would first analyze the query execution plan to identify bottlenecks, such as full table scans or inefficient joins. I would then optimize the query by adding appropriate indexes to the related tables, rewriting the query to reduce complexity, or breaking it into smaller, more efficient queries. After implementing these changes, I would test the query to ensure improved performance and monitor its execution to confirm the optimization is effective.

Suppose a team is experiencing frequent deployment failures. What steps would you take to improve the deployment process?</br>
I would analyze logs to identify failure patterns, strengthen testing, standardize the deployment pipeline, implement rollback mechanisms, set up monitoring and alerts, conduct post-mortems, and foster team collaboration to create a more reliable and efficient deployment process.

How would you handle a situation where a team or yourself is struggling with adopting new technology?</br>
I believe maintaining a positive mindset and a willingness to learn are crucial. I would encourage the team to embrace the challenge by breaking down the learning process into manageable steps, providing access to training resources, and fostering a collaborative environment where everyone can share knowledge and support each other. Additionally, I would set realistic goals, celebrate small wins, and seek guidance from experts if needed to ensure a smooth transition and successful adoption.


Coding Test

Instructions</br>
For the coding test, candidates are expected to demonstrate their problem-solving skills and creativity. Please follow these guidelines:</br>
Honesty: Please solve the test with honesty. We value original work and will evaluate your test based on your creativity and thinking.</br>
Programming Language: You can use any programming language that you find suitable for the tasks.</br>
Explanation: Providing explanations or comments in your code will be beneficial. This helps us understand your thought process and design decisions.</br>
Submission: You can submit your solutions in a document or create a GitHub repository and share the link with us. Please ensure that your repository is accessible and well-organized.</br>


Write a function that takes a list of integers and returns the sum of all even numbers.</br>

	function sumOfEvenNumbers(numbers) {
	    let sum = 0;
	    for (let number of numbers) {
	        if (number % 2 === 0) { // Check if the number is even
	            sum += number;
	        }
	    }
	    return sum; // return the value
	}
	
	const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
	console.log(sumOfEvenNumbers(numbers)); // Output: 30

Implement a simple sorting algorithm (e.g., bubble sort) for a list of integers.</br>

	function insertionSort(arr) {
	  for (let aa = 1; aa < arr.length; aa++) { // Loop from the second element to the end of the array
	    let current = arr[aa]; // Store the current element
	    let prev = aa - 1; // Initialize the previous element index
	    while (prev >= 0 && arr[prev] > current) { // Shift elements of the sorted segment forward if they are larger than the current element
	      arr[prev + 1] = arr[prev];
	      prev--;
	    }
	    
	    arr[prev + 1] = current; // Place the current element in its correct position
	  }
	  return arr;
	}
	
	$(document).ready(function() {
	  const unsortedArray = [123,55,21,65,232,7,11,89,3];
	      console.log('Unsorted Array: '+unsortedArray.join(', ')); // Display the unsorted array
	      const sortedArray = insertionSort(unsortedArray.slice()); // call insertionSort funtion
	      console.log('Sorted Array: '+sortedArray.join(', ')); // Display the sorted array
	
	    //Output : 
	    //"Unsorted Array: 123, 55, 21, 65, 232, 7, 11, 89, 3"
	    //"Sorted Array: 3, 7, 11, 21, 55, 65, 89, 123, 232"
	});

Design a simple RESTful API to manage a to-do list (create, read, update, delete tasks)</br>

	<?php 
	
	header("Content-Type: application/json");
	header("Access-Control-Allow-Origin: *");
	header("Access-Control-Allow-Methods: GET, POST, PUT, DELETE, OPTIONS");
	
	$todoFile = "todolist.json"; // file to store the json data.
	
	if (!file_exists($todoFile)) { // to check file exists
	    file_put_contents($todoFile, json_encode([]));
	}
	
	function readTodos($file) { // to read and decode file
	    $todosJson = file_get_contents($file);
	    return json_decode($todosJson, true);
	}
	
	function saveTodos($todos, $file) { // to encode and save data to file
	    file_put_contents($file, json_encode($todos, JSON_PRETTY_PRINT));
	}
	
	// retrieve HTTP method and request URL
	$method = $_SERVER["REQUEST_METHOD"];
	$uri = parse_url($_SERVER['REQUEST_URI'], PHP_URL_PATH);
	$uriParts = explode("/", trim($uri, "/"));
	
	// /api/todo @ /api/todo/{id}
	if (count($uriParts) < 2 || $uriParts[0] !== "api" || $uriParts[1] !== "todo") {
	    http_response_code(404);
	    echo json_encode(["message" => "Endpoint not found"]);
	    exit;
	}
	
	$id = null;
	//get id from URL
	if (isset($uriParts[2]) && is_numeric($uriParts[2])) {
	    $id = (int)$uriParts[2];
	}
	
	//load data from file
	$todos = readTodos($todoFile);
	
	// Switch based on HTTP method.
	switch ($method) {
	    case "GET":
	        //if got ID, return based on ID, else return all data
	        if ($id === null) {
	            echo json_encode($todos);
	        } else {
	            $found = null;
	            foreach ($todos as $todo) {
	                if ($todo["id"] === $id) {
	                    $found = $todo;
	                    break;
	                }
	            }
	            if ($found === null) {
	                http_response_code(404);
	                echo json_encode(["message" => "Todo not found"]);
	            } else {
	                echo json_encode($found);
	            }
	        }
	        break;
	
	    case "POST":
	        //add new todo item.
	        $data = json_decode(file_get_contents("php://input"), true);
	        if (!isset($data["name"])) {
	            http_response_code(400);
	            echo json_encode(["message" => "Invalid data; 'name' is required"]);
	            exit;
	        }
	
	        //auto-generate ID based on max id
	        $maxId = 0;
	        foreach ($todos as $todo) {
	            if ($todo["id"] > $maxId) {
	                $maxId = $todo["id"];
	            }
	        }
	        $newTodo = [
	            "id" => $maxId + 1,
	            "name" => $data["name"],
	            "isComplete" => isset($data["isComplete"]) ? (bool)$data["isComplete"] : false,
	        ];
	
	        $todos[] = $newTodo;
	        saveTodos($todos, $todoFile);
	        http_response_code(201);
	        echo json_encode($newTodo);
	        break;
	
	    case "PUT":
	        //update todo item based on id.
	        if ($id === null) {
	            http_response_code(400);
	            echo json_encode(["message" => "Todo ID is required for update"]);
	            exit;
	        }
	        $data = json_decode(file_get_contents("php://input"), true);
	        $foundIndex = null;
	        foreach ($todos as $index => $todo) {
	            if ($todo["id"] === $id) {
	                $foundIndex = $index;
	                break;
	            }
	        }
	        if ($foundIndex === null) {
	            http_response_code(404);
	            echo json_encode(["message" => "Todo not found"]);
	            exit;
	        }
	        // Update properties if provided
	        if (isset($data["name"])) {
	            $todos[$foundIndex]["name"] = $data["name"];
	        }
	        if (isset($data["isComplete"])) {
	            $todos[$foundIndex]["isComplete"] = (bool)$data["isComplete"];
	        }
	        saveTodos($todos, $todoFile);
	        http_response_code(204); // No content
	        break;
	
	    case "DELETE":
	        //delete todo item based on id.
	        if ($id === null) {
	            http_response_code(400);
	            echo json_encode(["message" => "Todo ID is required for deletion"]);
	            exit;
	        }
	        $foundIndex = null;
	        foreach ($todos as $index => $todo) {
	            if ($todo["id"] === $id) {
	                $foundIndex = $index;
	                break;
	            }
	        }
	        if ($foundIndex === null) {
	            http_response_code(404);
	            echo json_encode(["message" => "Todo not found"]);
	            exit;
	        }
	        array_splice($todos, $foundIndex, 1);
	        saveTodos($todos, $todoFile);
	        http_response_code(204);
	        break;
	
	    default:
	        http_response_code(405);
	        echo json_encode(["message" => "Method not allowed"]);
	        break;
	}

 	//    Get all to-do item
	//    GET : /api/todo
	
	//    Get specific to-do item based on id
	//    GET : /api/todo/{id}
	
	//    Add new to-do item
	//    POST : /api/todo
	
	//    Update existing to-do item based on id
	//    POST : /api/todo/{id}
	
	//    Delete to-do item based on id
	//    DELETE : /api/todo/{id}
	?>

Suppose you need to optimize a slow database query. How would you approach this?</br>
Example for MSSQL:</br>
View the Execution Plan to find the bottleneck.</br>
Add Indexes to related tables.</br>
Add SET STATISTIC IO ON; SET STATISTIC TIME ON; to see how many logical reads.</br>
Use SQL Server Profiler, to capture and analyze detailed query performance data.


Write a function that finds the first duplicate in an array of integers.</br>

	using System;
	using System.Collections.Generic;
	
	public class DuplicateFinder
	{
	    public static int FindFirstDuplicate(int[] numbers)
	    {
	        if (numbers == null || numbers.Length == 0)
	            throw new ArgumentException("Input array cannot be null or empty.");
	
	        HashSet<int> seen = new HashSet<int>();
	        foreach (int number in numbers)
	        {
	            if (seen.Contains(number))
	            {
	                // Found the first duplicate
	                return number;
	            }
	            seen.Add(number);
	        }
	        return -1; //if no duplicate exists, the function returns -1
	    }
	
	    public static void Main()
	    {
	        int[] toCheck = { 3,2,5,1,2,5,7,9,3,1,5 };
	        int duplicate = FindFirstDuplicate(toCheck); //call function and pass the data
	        
	        if (duplicate != -1)
	        {
	            Console.WriteLine("The first duplicate is: " + duplicate);
	        }
	        else
	        {
	            Console.WriteLine("No duplicate found.");
	        }
	    }
	}
	
	//output : 
	//The first duplicate is: 2


FizzBuzz Variant

Write a pseudocode and/or flowchart for a program that prints numbers from 1 to 20 with the following rules:</br>
If the number is divisible by 3, print “Fizz”.</br>
If the number is divisible by 5, print “Buzz”.</br>
If the number is divisible by both 3 and 5, print “FizzBuzz”.</br>
Otherwise, print the number itself.</br>
		
    START
       SET i = 1
       WHILE i ≤ 20 DO	//loop 1 to 20
           IF (i mod 3 == 0) AND (i mod 5 == 0) THEN	// if i/3=0 or i/5=0 then FizzBuzz
               PRINT "FizzBuzz"
           ELSE IF (i mod 3 == 0) THEN	// if i/3=0 then Fizz
               PRINT "Fizz"
           ELSE IF (i mod 5 == 0) THEN	// if i/5=0 then Buzz
               PRINT "Buzz"
           ELSE
               PRINT i
           END IF
           SET i = i + 1
       END WHILE
    END


Grading System

Write pseudocode and/or draw a flowchart for a program that takes a student’s score (0-100) as input and prints their grade based on the following criteria:</br>
80 - 100 Grade A</br>
61 - 79 Grade B</br>
41 - 60 Grade C</br>
21 - 40 Grade D</br>
0 - 20 Grade F</br>

    START
      INPUT score
    
      IF score < 0 OR score > 100 THEN	//only valid for 1 - 100
          PRINT "Invalid score"
      ELSE
          IF score >= 80 THEN
              PRINT "Grade A"
          ELSE IF score >= 61 THEN
              PRINT "Grade B"
          ELSE IF score >= 41 THEN
              PRINT "Grade C"
          ELSE IF score >= 21 THEN
              PRINT "Grade D"
          ELSE
              PRINT "Grade F"
          END IF
      END IF
    END



Min and Max Number

Write pseudocode and/or draw a flowchart for a program that takes 5 numbers as input and determines both the largest and smallest numbers among them.</br>

    BEGIN
      DECLARE num[5], largest, smallest
    
      FOR i FROM 1 TO 5 DO
          PRINT "Enter number ", i
          READ num[i]
      END FOR
    
      SET largest = num[1]
      SET smallest = num[1]
    
      FOR i FROM 2 TO 5 DO
          IF num[i] > largest THEN
              SET largest = num[i]
          END IF
          IF num[i] < smallest THEN
              SET smallest = num[i]
          END IF
      END FOR
    
      PRINT "Largest number: ", largest
      PRINT "Smallest number: ", smallest
    END


The Triangle

Write a program that prints an equilateral triangle using a specified character (* by default). The user should be able to input the height (n) of the triangle.
Requirements:</br>
The program should prompt the user to enter the height (n).</br>
It should print an equilateral triangle of height n.</br>
The triangle should be centered, ensuring proper spacing for alignment.</br>
The solution should work for any programming language.</br>
Ensure proper error handling for invalid inputs.</br>

	function printEquilateralTriangle(n) {
	    if (!Number.isInteger(n) || n <= 0) {
	        console.log("Invalid input. Please enter a positive integer.");
	        return;
	    }
	
	    for (let i = 1; i <= n; i++) {
	        // Print leading spaces
	        console.log(" ".repeat(n - i) + "*".repeat(2 * i - 1));
	    }
	}
	
	// Prompt user for input
	let n = parseInt(prompt("Enter the height (n) of the equilateral triangle:"));
	printEquilateralTriangle(n);


Game-Specific Questions


What motivated you to get into game development?</br>
I want to try something new in my career, and game development feels like the perfect fit. I love playing games, and this passion inspires me to create my own. I want to contribute to the medium I enjoy while exploring new creative and technical challenges. Besides that, the gaming industry is a rapidly growing field that offers exciting career opportunities, and I’m eager to be part of its future.

What are your favorite video games, and why?</br>
I have many favorite games, including Dota 2, Clash of Clans, Counter Strike, Minecraft and FIFA. These games help me relieve stress, connect with new friends in the gaming community, and sharpen my critical thinking skills to win matches. For example, Dota 2 and Counter Strike challenge my teamwork and strategy, while Clash of Clans allows me to build and manage my own base, which I find relaxing. FIFA, on the other hand, lets me enjoy my love for soccer and compete with friends.

What do you think makes a game fun and engaging?</br>
What makes a game fun and engaging for me is a combination of satisfying gameplay, a compelling story, and a sense of progression. For example, I love games like Dota 2 that keep me hooked with its strategic depth and competitive multiplayer. A good balance of challenge and reward is also crucial, games should feel rewarding to play without being too easy or frustrating. Lastly, I appreciate games that allow for creativity or social interaction, like Minecraft or Among Us, as they offer unique experiences that keep me coming back.

Why do you want to work in the gaming industry?</br>
As I mentioned earlier, I believe the gaming industry is a rapidly growing field with exciting career opportunities, and I’m eager to be part of its future. I’ve always loved playing games, and now I want to contribute by creating engaging experiences for others. Working in this industry allows me to combine my passion for gaming with my desire to innovate and grow professionally.



Final Notes

Thank you for taking the time to complete this assessment. We appreciate your effort and look forward to reviewing your submissions.</br>
Good Luck! We wish you the best of luck in completing this assessment. Please don’t feel pressured to answer every question perfectly—just do your best and submit what you can within the given timeframe.</br>
Submission Reminder: Ensure that you submit your work before the deadline. If you have any questions or need clarification on any of the tasks, feel free to reach out to us.</br>
Thank you again for your participation, and we look forward to reviewing your work!</br>

