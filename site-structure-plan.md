# Site Structure Plan

## Current State
- `index.html`: Main page with cat information
- `style.css`: Shared stylesheet
- `images/`: Directory with cat images

## Proposed New Structure
1. Keep `index.html` as the main landing page
2. Create `about.html` for detailed cat descriptions
3. Maintain consistent styling through shared CSS

## About Page Content Plan

### Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Malla - My Cat's Kingdom</title>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>About Malla</h1>
    <nav>
      <a href="index.html">← Back to Main Page</a>
    </nav>
  </header>
  
  <main>
    <section class="cat-qualities">
      <h2>Malla's Notable Qualities</h2>
      <ul class="qualities-list">
        <li>She is a great lover of all things catnip.</li>
        <li>She is a great napper.</li>
        <li>She is a great eater of lettuce and strawberry tops.</li>
        <li>She carries the quiet wisdom of twilight in her gaze, and the soft grace of shadows in her step.</li>
        <!-- More qualities to be added -->
      </ul>
    </section>
    
    <!-- More sections as needed -->
  </main>
</body>
</html>
```

## Main Page Update Plan

### Add Link to About Page
```html
<!-- In index.html, add this section where appropriate -->
<section class="about-link">
  <h2><a href="about.html">About Her</a></h2>
</section>
```

## CSS Considerations
- Ensure links are styled appropriately
- Consider adding navigation styling for moving between pages
- Maintain consistent typography and color scheme