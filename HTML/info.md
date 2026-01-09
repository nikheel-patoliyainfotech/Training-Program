Project Structure (Conceptual)

Header / Title

A heading for the page (e.g., <h1>Personal Profile Form</h1>).

Helps organize content and improve accessibility.

Form Section

Purpose: Collect user information such as name, email, password, age, gender, hobbies, and country.

Tags to Practice: <form>, <input>, <textarea>, <select>, <option>, <datalist>, <button>, <fieldset>, <legend>

Form Attributes:

action (where data is sent)

method (GET or POST)

novalidate (disable default browser validation for practice)

autocomplete (help browsers fill info automatically)

Validation:

Required fields (required)

Minimum and maximum lengths (minlength, maxlength)

Patterns (pattern)

Custom messages (optional JavaScript)

Table Section

Purpose: Display submitted user profiles in a structured table.

Tags to Practice: <table>, <caption>, <thead>, <tbody>, <tfoot>, <tr>, <th>, <td>

Structure:

Caption at the top describing the table

Header row with column names

Body rows for user data

Footer row for summary or notes

Media Section

Purpose: Embed video, audio, and external content to practice media tags.

Tags to Practice: <video>, <audio>, <source>, <track>, <iframe>

Attributes:

controls (play, pause, etc.)

preload

kind and srclang for captions

loading="lazy" for iframe optimization

Accessibility Considerations

Labels: <label for> to associate text with input fields

Aria Descriptions: aria-describedby for additional instructions

Captions for media: <track> for videos

User Flow

User visits the page.

Fills out the form with personal details, selects choices (gender, hobbies, country), and optionally uploads a file.

Submits the form.

Submitted data appears in a table below the form (can start with sample static data).

User can interact with media elements (play video/audio or view iframe).