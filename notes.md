# CS 260 Notes

[My startup](https://simon.cs260.click)

## Helpful links

- [Course instruction](https://github.com/webprogramming260)
- [Canvas](https://byu.instructure.com)
- [MDN](https://developer.mozilla.org)

## Starting Notes

### Instructions for notes:
Your notes file is meant as a place to remember all the things you have learned from this course. You should modify this file frequently.

1. Read the GitHub documentation about the basics of writing markdown.
2. Access the file in your repository called notes.md. You can use the contents of this file on any exam. As you modify your notes.md file throughout the class. Make sure that you keep it organized and clean. You can add multiple .md files and reference them from your notes.md file in order make it easier to organize your content.
3. Make your first notes in your notes.md file about what you learned from this assignment. Commit and push your notes to GitHub.

### Initial Thoughts

As I already have a pretty good understanding of Git and GitHub, I am excited to start learning other tools. Having a notes.md file will be really helpful, and I should probably include them in many other projects

### Startup Specification

It's helpful to have a design document from the beginning to help guide. It might be helpful to change it as needed in the future.

Use the CatAPI.
Maybe keep track of user's time in game.
Colorblind option
Custom cat and/or Background maker

## AWS Notes

I initially used an old security group that I was not as sure with the settings, which I think led to being unable to access the server using ssh or http. I deleted the instance and made a new one with a new security group, and then it worked just fine.

I previously took this class and dropped it, without properly releasing my elastic IP, which led to a $3 charge for several months after. It is important to go through and fully ensure the instance, domain, and elastic IP are properly released, shut down, and deleted when we are done.'


### Route 53
After having some issues getting my domain, I reached out to AWS support (which was suggested by the email that said getting the domain failed) and, after several days, they lifted some kind of restriction and allowed me to lease derekawalton.com.

Additionally, once I finally got the domain onto my EC2 instance, I also enabled my VSCode to allow me to have an ssh connection and explore files without having to use Vi. This makes navigation and modification of files way easier. It involves a config file, but once you have connected once, VSCode saves everything for you for easy access, similar to how GitLens works in VSCode.

It feels amazing to be able to type in my name to get to my own website. So cool! Check out [derekawalton.com](derekawalton.com)

## Caddy Notes

Caddy seems to be a powerful and convenient tool. I installed the Go tool on VS Code to make the language helpfully colorful. Also, the easy change to putting my domain name in for my subdomains was awesome.

I had glanced over the directions for editing the Caddy file and failed to change the actual root address, making my subdomains secure but not [derekawalton.com](derekawalton.com). So I fixed that.

Again, I forgot to read through everything and failed to restart caddy once I fixed my root domain. Now it is working. See note below

> [!NOTE]
> Remember to fully read directions!!!

## HTML Notes

For the most part, HTML seems pretty simple, the only thing that can get confusing is all the different tags. Fortunately, the Simon example code is helpful and easy to understand.

I am debating whether to have the save button just say "Save" or be longer like "Save Cat and Environment to profile". The sizing might get too big on mobile once I implement CSS, so I'm leaning towards just "Save". I might find a way to have a hover message for more info so it is an option without taking up space all the time.

## CSS notes:


## Class notes:
"Believe more in yourself" - Dr. Jensen

### VI
- Starts in command mode
- I to insert mode (edit)
- :wq to write and quit
- ESC to go back to command mode
- :q! quits without saving changes

### Tools
Warp is a cool AI assisted terminal. I might install onto my linux computers. The old computers might be too slow, so I might just do it on the newer computer.