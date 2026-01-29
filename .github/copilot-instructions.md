# Copilot Instructions for C-Programming-MCQ Repository

## Repository Overview

This repository contains C++ programming multiple-choice question (MCQ) quiz applications built with HTML, CSS, and JavaScript. It serves as an educational resource for C++ interview preparation and programming concept review.

## Code Style and Standards

### HTML Files
- Always include the project header comment block at the top of HTML files:
  ```html
  <!-- ********************************************************************** -->
  <!--                                                                        -->
  <!--  filename.html                                     TTTTTTTT SSSSSSS II -->
  <!--                                                       TT    SS      II -->
  <!--  By: st93642@students.tsi.lv                          TT    SSSSSSS II -->
  <!--                                                       TT         SS II -->
  <!--  Created: <date> st93642                              TT    SSSSSSS II -->
  <!--  Updated: <date> st93642                                            -->
  <!--                                                                        -->
  <!--   Transport and Telecommunication Institute - Riga, Latvia             -->
  <!--                       https://tsi.lv                                   -->
  <!-- ********************************************************************** -->
  ```
- Use semantic HTML5 elements
- Maintain proper indentation (4 spaces)
- Use descriptive class names following BEM methodology where appropriate

### CSS
- Use CSS custom properties (CSS variables) for theming
- Follow a mobile-first approach for responsive design
- Use flexbox and grid for layouts
- Maintain consistent color schemes across pages

### JavaScript
- Keep JavaScript inline in HTML files (current pattern)
- Use modern ES6+ syntax
- Maintain clear function naming
- Add comments for complex logic
- Follow existing patterns for quiz functionality

## Project Structure

- `index.html` - Main C++ interview questions quiz
- `exam_answers_all_questions.html` - Complete review of all questions with answers
- `soc_analyst_guide.html` - SOC analyst career guide content
- PDF files - Educational resources (SOC analyst guides)

## Development Guidelines

1. **Quiz Features**: When adding or modifying quiz questions:
   - Ensure proper question numbering
   - Include clear answer options (A, B, C, D)
   - Provide detailed explanations for correct answers
   - Mark correct answers clearly in review mode

2. **User Interface**: 
   - Maintain consistent styling with gradient backgrounds
   - Use card-based layouts for questions
   - Ensure responsive design works on mobile devices
   - Keep color schemes consistent with existing pages

3. **Accessibility**:
   - Use appropriate ARIA labels
   - Ensure sufficient color contrast
   - Maintain keyboard navigation support
   - Add alt text for any images

4. **Performance**:
   - Minimize inline JavaScript where possible
   - Optimize images and assets
   - Keep file sizes reasonable

## Git Workflow

- Follow conventional commit messages
- Update both Created and Updated dates in file headers when modifying files
- Respect the `.gitignore` patterns (excludes JSON and JS files except specified HTML files)

## Educational Context

This repository is associated with the Transport and Telecommunication Institute in Riga, Latvia (https://tsi.lv). Content should be appropriate for educational use and maintain academic integrity.

## Testing

When making changes:
- Test quiz functionality in multiple browsers
- Verify responsive design on different screen sizes
- Check that scoring and answer validation works correctly
- Ensure all links and navigation work properly
