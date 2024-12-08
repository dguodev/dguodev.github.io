---
pageClass: home-page
# some data for the components

name: Dan Guo
profile: /dan.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/dguodev/
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/dguodev/


cv: https://www.linkedin.com/in/dguodev/
bio: Greater Toronto Area , Ontario , Canada 
email: dan@dguo.dev
---

<ProfileSection :frontmatter="$page.frontmatter" />
## About Me
Working at [lotusflare](https://lotusflare.com) . 
We are building next generation cloud native telco platform . 

## Experience
- [Oct 2021] Lotusflare , Server Engineering 
- [Jan 2014 – Oct 2021] Tata Consultancy Services CIBC,  Consultant , Backend and Operation
- [Dec 2012 – Dec 2013] Tata Consultancy Services Blackberry , Consultant , Full Stack
- [Sep 2011 – Dec 2012] Fingersoft Technology Ltd , Lead Engineer , Java web application
- [Jun 2007 – Sep 2011] Finalist , Senior Developer, Tech Lead, Java web application
- [Jun 2006 – Aug 2007] Peking University,Research Engineer
- [Jul 2003 – Jun 2006] CapitalBio,Java Developer

## Education
- University of Chinese Academy of Sciences Master of Computer Technology
- Hebei University of Technology Bachelor Electrical and Electronics Engineering

## Tools that i am using 
### terminal 
- [bat](https://github.com/sharkdp/bat)

### editor
- [Neovim](https://neovim.io/)

### IDE
- [Jetbrains IntelliJ IDEA](https://www.jetbrains.com/idea/) 
- [Cursor](https://www.cursor.com/)

### MISC
- [Perplexity](https://www.perplexity.ai/)
  

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
