<!DOCTYPE html>
<head>
</head>
<body>
  <h1>Popular Data Science Questions</h1>
  <p>The aim of this project is to help a company, that works in producing data science content on what best content to focus on.
The best content will be the one data science enthusiasts are more interested in learning.  
I am going to use <a href="https://datascience.stackexchange.com/" target="_blank">Data Science Stack Exchange</a> to determine what content should a data science education company create, based on interest by subject.</p>
  <h2>Stack Exchange</h2>
  <h3>What kind of questions are welcome on this site?</h3>
  <p>On DSSE's <a href="https://datascience.stackexchange.com/help" target="_blank">help centre's</a> section on questions , we can read that we should:<p>
  <ul>
    <li>Ask questions that are practical, answerable, based on actual problems that one faces.</li>
    <li>Questions should be reasonably scoped.</li>
    <li>Avoid subjective questions.</li>
  </ul>
  <h3>What, other than questions, does the site's home subdivide into?</h3>
  <p>On the <a href="https://datascience.stackexchange.com/" target="_blank">home page</a> we can see that we have four sections:</p>
  <ul>
     <li><a href="https://datascience.stackexchange.com/questions" target="_blank">Questions</a> - A list of all questions asked</li>
     <li><a href="https://datascience.stackexchange.com/tags" target="_blank">Tags</a> - A list of keywords that categorize questions</li>
     <li><a href="https://datascience.stackexchange.com/users" target="_blank">Users</a> - A list of users</li>
     <li><a href="https://datascience.stackexchange.com/unanswered" target="_blank">Unanswered</a> - A list of questions with no upvoted or accepted answers</li>
  </ul>
  <p>The tagging system used by Stack exchange will help us solve our problem, as it enablesus quantify how many questions are asked about each subject. <br> Since Stack Exchange's sites are heavily moderated by the community; this gives us some confidence in using the tagging system to derive conclusions.</p>
  <h3>What information is available in each post?</h3>
  <p>Looking, just as an example, at <a href="https://datascience.stackexchange.com/questions/81656/question-about-alphago-zeros-neural-network-architecture" target="_blank">this</a> question, some of the information we see is:</p>
  <ul>
    <li>For both questions and answers:</li>
    <ul type="square">
      <li>The posts's score</li>
      <li>The posts's title</li>
      <li>The posts's author</li>
      <li>The posts's body</li>
    </ul>
  </ul>
  <ul>
  <li>For questions only:</li>
   <ul type="square">
    <li>How many users have it on their "</li>
    <li>The last time the question as active</li>
    <li>How many times the question was viewed</li>
    <li>Related questions</li>
    <li>The question's tags</li>
   </ul>
  </ul>
  <h3>Stack Exchange Data Explorer</h3>
  <p>Stack Exchange provides a public <a href="https://data.stackexchange.com/datascience/query/new" target="_blank">data base</a> for each of its websites. <br> The tables that look promising towards finding the most popular content include:</p>
  <ul>
    <li>Posts</li>
    <li>PostTags</li>
    <li>Tags</li>
    <li>TagSynonyms</li>
  </ul>
  <p>Running a few exploratory queries, leads us to focus our efforts on Posts table.</p> 
  
  
