# week 8
**Date** 30/03/2025

## Learning Activities & Resources

### Hypothesis  
**Using a locally hosted WordPress installation (via XAMPP) provides greater flexibility and control for learning theme development compared to using a managed hosting service like AWS.com.**

### Test Design  
**Background:**  
In previous weeks, I have been using a locally hosted WordPress installation for theme development and experimentation. I’ve also created accounts on WordPress.com and tested their hosted offering. This week, I aim to compare both environments in terms of control, learning efficiency, and developer experience.

**Key Criteria for Comparison:**
1. **Theme Customisation Capability**  
2. **File Access and Flexibility (e.g. `wp-content`, `functions.php`)**  
3. **Plugin Access and Limitations**  
4. **Performance / Loading Speed**  
5. **Ease of Setup**  
6. **Risk of Mistakes and Recovery**  

**Method A – Local WordPress (XAMPP):**
- Installed WordPress locally via XAMPP  
- Set up a child theme and made multiple code-level changes (CSS, PHP)  
- Had full access to file system via VS Code  

**Method B – Hosted WordPress (AWS.com Free Plan):**
- Created a free WordPress.com site  
- Attempted the same level of theme customisation using the theme editor and customiser  
- Plugin installation and file access were restricted  

### Results  
| Criteria                        | Local (XAMPP)                   | Hosted (AWS.com)               |
|--------------------------------|----------------------------------|--------------------------------------|
| Theme Customisation            | Full code-level control          | Limited to CSS and theme options     |
| File Access                    | Full access via file manager     | No access to theme files or PHP      |
| Plugin Flexibility             | Unlimited (can upload any)       | Restricted or paid-only              |
| Performance                    | Fast locally                     | Sometimes slow due to free plan      |
| Setup Effort                   | Medium (manual setup required)   | Very easy, quick one-click setup     |
| Learning Value                 | High (learned actual structure)  | Low to medium (interface only)       |
| Mistake Recovery               | Simple (can reset easily)        | Restricted, must contact support     |

**Summary:**  
- Local environment offers more control and a realistic development experience, especially useful for learning theme development and plugin integration  
- Hosted solutions are beginner-friendly but limit deeper exploration unless on a paid plan  
- Local setup gives direct exposure to WordPress architecture and PHP/HTML/CSS integration

## Estimated Hours
**Approximately 3 hours**

## Content Insights
- Learned how different WordPress environments affect what you can and cannot do  
- Understood that hosted platforms are ideal for **content creators**, but less suited for **developers**  
- Realised the importance of full file access when working with child themes and advanced customisation  
- Gained appreciation for tools like XAMPP in learning server-side concepts locally

## Career / Employability / Learning Insights
- Practicing in a local environment provides **real-world development skills**, such as file structure management, code editing, and troubleshooting  
- Helps prepare for **client or agency work**, where local development, staging, and deployment workflows are standard  
- Hosted services are useful for **quick demos** or **non-technical users**, but not ideal for developers  
- Learning the differences strengthens decision-making skills when selecting hosting for future projects or clients  
- Demonstrated the ability to compare tools and environments critically — a key skill in tech careers