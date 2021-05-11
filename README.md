# HTML Interview

In this assignment, we'll work in groups of 2-3 students. This is a great time to meet your fellow classmates!

Although we're working in groups for this assignment, we'll still turn in separate code submissions.

## Instructions

#### Part 0: Project set up

Start off by forking this repository. Forking an existing repository is just like creating a new one except that your new repository will contain a copy of the forked code. 

After forking the repository, enable GitHub Pages. To do this, go to the Settings tab of your repository, then go to Pages on the left. Change source to 'Main' or 'Master' depending on which option you have. Then click save. The page should refresh and a URL to your hosted project should be visible.

Finally, copy that URL, navigate back to the home page of your repository, click the gear icon next to the 'About' section on the right, and set the 'Website' of your project to be this GitHub Pages URL.

#### Part 1: Ten questions, ten answers

As a group, think of ten total questions that you can ask one another and record the answers to.

Have each person answer the ten questions. Write down both the questions and their answers.

#### Part 2: Building an HTML page



Now that you have all the questions and answers, its time to display them in HTML. 

We'll create a section on the page for each student's answers.

* Start out by creating an empty HTML page with the HTML starter code
* Create 2-3 `<div>` elements in the `<body>` section of the HTML, one for each student
* Inside each `<div>`
  * Create a header (either `<h1>`, `<h2>`, etc) with the student's name
  * Under the header, create an anchor tag that links to the student's GitHub page
  * Under the link, add an image of the student, set the image's height to `250px`
  * And finally, create an ordered list that contains a list item for each question and answer
    * Each question and answer should be stored in a single list item element (`<li>`)
    * The question part of the list item should be bolded


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interview</title>
</head>
<body>
    <div>
    <h1>Ben(Ban)</h1>
    <h4><a href="https://github.com/banjman81">Ben's github</a></h4>
    <input type="image" src="/images/IMG_3156.jpg" alt="myPic" height="250px"/>
        <ol>
            <li><b>What is your favorite food?</b>
                <ul>
                    <li>Poke Bowl and Ramen</li>
                </ul>
            </li>
            <li><b>How old are you?</b>
                <ul>
                    <li>24</li>
                </ul>
            </li>
            <li><b>Where are you from?</b>
                <ul>
                    <li>Myanmar</li>
                </ul>
            </li>
            <li><b>What is you favorite movie?</b>
                <ul>
                    <li>all of MCU</li>
                </ul>
            </li>
            <li><b>What is you favorite animal?</b>
                <ul>
                    <li>Badgers</li>
                </ul>
            </li>
            <li><b>What hobbies do you enjoy?</b>
                <ul>
                    <li>Video Game</li>
                </ul>
            </li>
            <li><b>What was the last place you visited?</b>
                <ul>
                    <li>Oahu Hawaii</li>
                </ul>
            </li>
            <li><b>Have you ever own a pet?</b>
                <ul>
                    <li>Yes, dog, cat and snake.</li>
                </ul>
            </li>
            <li><b>What is your goal after this course?</b>
                <ul>
                    <li>Be the nect Elon Musk.</li>
                </ul>
            </li>
            <li><b>Who is your favorite celebrity?</b>
                <ul>
                    <li>Elon Musk</li>
                </ul>
            </li>
        </ol>
    </div>
    <div>
    <h1>Jacques</h1>
    <h4><a href="https://github.com/jacquesjg">Jacques's github</a></h4>
    <input type="image" src="" alt="myPic" height="250px"/>
        <ol>
            <li><b>What is your favorite food?</b>
                <ul>
                    <li>Pizza.</li>
                </ul>
            </li>
            <li><b>How old are you?</b>
                <ul>
                    <li>27</li>
                </ul>
            </li>
            <li><b>Where are you from?</b>
                <ul>
                    <li>Brooklyn, NY</li>
                </ul>
            </li>
            <li><b>What is you favorite movie?</b>
                <ul>
                    <li>Shawshank Redemption</li>
                </ul>
            </li>
            <li><b>What is you favorite animal?</b>
                <ul>
                    <li>Tiger</li>
                </ul>
            </li>
            <li><b>What hobbies do you enjoy?</b>
                <ul>
                    <li>Language learning (human language)</li>
                </ul>
            </li>
            <li><b>What was the last place you visited?</b>
                <ul>
                    <li>London</li>
                </ul>
            </li>
            <li><b>Have you ever own a pet?</b>
                <ul>
                    <li>Yes, dogs</li>
                </ul>
            </li>
            <li><b>What is your goal after this course?</b>
                <ul>
                    <li>Digital nomad</li>
                </ul>
            </li>
            <li><b>Who is your favorite celebrity?</b>
                <ul>
                    <li>Leonel Messi</li>
                </ul>
            </li>
        </ol>
    </div>
    <div>
    <h1>Readus</h1>
    <h4><a href="https://github.com/hartr117">Readus's github</a></h4>
    <img src=/images/image_3459.jpeg?raw=true" alt="myPic" height="250px"/>
        <ol>
            <li><b>What is your favorite food?</b>
                <ul>
                    <li>Pizza</li>
                </ul>
            </li>
            <li><b>How old are you?</b>
                <ul>
                    <li>44</li>
                </ul>
            </li>
            <li><b>Where are you from?</b>
                <ul>
                    <li>Indiana</li>
                </ul>
            </li>
            <li><b>What is you favorite movie?</b>
                <ul>
                    <li>Dune</li>
                </ul>
            </li>
            <li><b>What is you favorite animal?</b>
                <ul>
                    <li>Wildebeest</li>
                </ul>
            </li>
            <li><b>What hobbies do you enjoy?</b>
                <ul>
                    <li>Surf Internet</li>
                </ul>
            </li>
            <li><b>What was the last place you visited?</b>
                <ul>
                    <li>Kentucky</li>
                </ul>
            </li>
            <li><b>Have you ever own a pet?</b>
                <ul>
                    <li>No</li>
                </ul>
            </li>
            <li><b>What is your goal after this course?</b>
                <ul>
                    <li>Work from home</li>
                </ul>
            </li>
            <li><b>Who is your favorite celebrity?</b>
                <ul>
                    <li>Clint Eastwood</li>
                </ul>
            </li>
        </ol>
    </div>
</body>
</html>

