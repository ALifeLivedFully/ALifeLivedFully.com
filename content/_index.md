---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true
  - block: markdown
    content:
      title: '📚 My Work'
      subtitle: ''
      text: |-
        I'm a software engineer with a passion for digging into complex systems, learning across disciplines, and building things that are both functional and meaningful. Whether I'm writing code, exploring public safety tech, or experimenting with digital tools through ALifeLivedFully, I'm driven by curiosity and a deep respect for hands-on learning.
        
        I love exploring where technology meets real life—especially when it helps people live more freely, creatively, or securely.

        If you're working on something interesting (or weird or wild), feel free to [reach out](/#contact-me)-I'm always open to collaborating 😄
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent Blogs & News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    id: contact-me
    content:
      title: '📞 Contact me 📞'
      subtitle: ''
      text: |-
        I accept donations on [Ko-Fi](https://ko-fi.com/ALifeLivedFully) and you can find my socials [Here](https://links.alifelivedfully.com)

        <div style="text-align: center; margin-top: 50px;">
        <form id="contact-form" action="mail.php" method="POST" style="display: inline-block;">
        <div class="row"><div class="col-lg-6">
            <input type="text" class="form-control" maxlength="30" name="name" id="name" placeholder="Name" required="">
        </div>
        <div class="col-lg-6">
            <input type="text" minlength="10" maxlength="20" class="form-control" name="phone" id="phone" placeholder="Phone Number">
        </div>
        <div class="col-lg-6">
            <input type="email" class="form-control" minlength="6" maxlength="100" name="email" id="email" placeholder="Email" required="">
        </div>
        <div class="col-lg-6">
            <div class="select-wrapper">
                <select class="form-control" id="projectType" name="project-type" required="">
                    <option value="" selected="" disabled="" hidden="">Project Type</option>
                    <option value="Web Development">Web Development</option>
                    <option value="Systems Automation">Systems Automation</option>
                    <option value="Self Sufficiency Education">Self Sufficiency Education</option>
                    <option value="Sustainability Education">Sustainability Education</option>
                    <option value="Other">Other</option>
                </select>
            </div>
        </div>
        <div class="col-12">
            <textarea required="" minlength="40" maxlength="1000" class="form-control" id="aboutProject" name="about-project" rows="6" placeholder="About the Project"></textarea>
        </div>
        <div class="h-captcha" data-theme="dark" data-sitekey="bf3e6e94-bf16-474c-9bc0-f0180430e490"></div>
        <div class="col-13">
            <button name="submit" type="submit" class="btn btn-primary" id="contact-form-button"><span class="btn-area"><span data-text="Send Message">Send Message</span></span></button>
        </div>
        </form>
        </div>

        <script src="https://js.hcaptcha.com/1/api.js" async defer></script>
    design:
      columns: '1'
  # - block: cta-button-list
  #   content:
  #     # Need a custom icon?
  #     # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
  #     buttons:
  #       - text: Read my latest paper on LLMs
  #         icon: academicons/arxiv
  #         url: https://arxiv.org/abs/2304.01852
  #       - text: Watch my new YouTube video to achieve 20x productivity
  #         icon: brands/youtube
  #         url: https://youtube.com
  #       - text: Connect with me on LinkedIn
  #         icon: brands/linkedin
  #         url: https://linkedin.com
---
