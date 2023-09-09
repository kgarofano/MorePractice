# MorePractice
Figuring my way around GitHub
echo "# Fullstack-Practice-Exercises" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kgarofano/Fullstack-Practice-Exercises.git
git push -u origin main
//fingers crossed I've done this correctly//

<p>My cat is <strong>very</strong> grumpy</p>

sequenceDiagram
    participant browser
    participant server
    
 browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/new_note
    activate server
    server-->>browser: HTML document
    deactivate server
    
  browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/main.css
    activate server
    server-->>browser: the css file rendering new note
    deactivate server

  browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    activate server
    server-->>browser: [{ new note appears }] 
    deactivate server
    Note right of browser: The browser executes the callback function that renders the new note 
    
 

    
