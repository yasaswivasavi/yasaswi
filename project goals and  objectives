const express = require('express');
const bodyParser = require('body-parser');
const app = express();
const port = 3001; // Choose your desired port

app.use(bodyParser.json());

// Sample projects data
const projects = [
  { 
    id: 1, 
    name: 'Project A', 
    goals: ['Goal 1', 'Goal 2', 'Goal 3'],
    objectives: ['Objective 1', 'Objective 2', 'Objective 3']
  },
  { 
    id: 2, 
    name: 'Project B', 
    goals: ['Goal A', 'Goal B', 'Goal C'],
    objectives: ['Objective X', 'Objective Y', 'Objective Z']
  },
  // Add more projects as needed
];

// API endpoint to get all projects
app.get('/api/projects', (req, res) => {
  res.json(projects);
});

// Add more API endpoints for other functionalities (create, update, delete, etc.)

app.listen(port, () => {
  console.log(`Server is running on port ${port}`);
});