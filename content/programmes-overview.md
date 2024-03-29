---
title: Our Programmes
subtitle: The core of what we do
draft: false
include_footer: true
---
At the core of what we do are our Programmes. **Currently, we run two programmes each semester: our Analyst Training Programme and Senior Analyst Programme**. It is through these programmes that students at the University of Edinburgh can become a part of Prosper, get first-hand experience with socially responsible investments and receive top quality training experiences.

![Some members on our programmes](/images/pinboard-design.png)

All Prosper Analysts complete an initial eight-week training programme, as well as ongoing training throughout their Prosper careers. **We work with students from all academic and social backgrounds who share our values**.

Our Programmes aim to equip Analysts and Senior Analysts with the knowledge and skills to start making socially responsible investments and will prepare them to make a positive impact in the future.

<div style="width: wrap; margin: auto; text-align: center; margin: 20px 0px 20px;">

<a href="/training">
<span class="button signup-button rounded secondary-btn raised" style="width: 250px; margin: auto; margin-top: 5px; margin-bottom: 5px;">
    Analysts
</span>
</a>

<a href="/senior-analyst-programme">
<span class="button signup-button rounded secondary-btn raised" style="width: 250px; margin: auto; margin-top: 5px; margin-bottom: 5px;">
    Senior analysts
</span>
</a>

</div>

### Be a part of the Prosper community

We have formed a strong community of like-minded individuals who are interested in finance and want to make a difference. By joining us as an analyst or senior analyst you can become part of the community and join us in our mission to make an impact through socially responsible investments.

![Our community structure](/images/community-structure.png)

### Frequently asked questions

<div class="accordion">
  <div class="accordion-item">
    <div class="accordion-item-header">
      What is the Prosper community like?
    </div>
    <div class="accordion-item-body">
      <div class="accordion-item-body-content">
        We are a diverse group of students who come from a wide range of academic backgrounds. What brings us together? Our passion for making a difference and using finance to do so! We want to challenge traditional perceptions and stereotypes of finance and aim to achieve that through our actions. We embrace all individuals regardless of their background, and always foster a positive and progressive atmosphere.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <div class="accordion-item-header">
      How do I make a positive social impact through Prosper’s programmes?
    </div>
    <div class="accordion-item-body">
      <div class="accordion-item-body-content">
        You make both a direct and indirect positive social impact - that’s the beauty with Prosper. Your involvement with our investments as a fund will ensure we make a positive social impact by supporting companies who deserve it and who will make an impact themselves. You also have a say in how you feel Prosper can expand its social impact by proposing projects. Since we are young, we have yet to fully develop our social impact strategy. You can also help manifest our current and future projects.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <div class="accordion-item-header">
      I really want to get involved but I am not a student from Edinburgh University. What can I do?
    </div>
    <div class="accordion-item-body">
      <div class="accordion-item-body-content">
        Get in touch! We’d love to hear from you and see how you could get involved with Prosper outside of our Programmes. We also host events and post a Blog which you can access through our website and social media pages. Also, don’t forget to sign up to our mailing list for all things Prosper!
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <div class="accordion-item-header">
      How can I join the Management Team?
    </div>
    <div class="accordion-item-body">
      <div class="accordion-item-body-content">
        Only Prosper’s Analysts and Senior analysts who have completed the Analyst Training Programme can apply to join the Management Team.
      </div>
    </div>
  </div>
</div>

<script>
    const accordionItemHeaders = document.querySelectorAll(".accordion-item-header");

accordionItemHeaders.forEach(accordionItemHeader => {
  accordionItemHeader.addEventListener("click", event => {
    
    // Uncomment in case you only want to allow for the display of only one collapsed item at a time!
    
    const currentlyActiveAccordionItemHeader = document.querySelector(".accordion-item-header.active");
    if(currentlyActiveAccordionItemHeader && currentlyActiveAccordionItemHeader!==accordionItemHeader) {
      currentlyActiveAccordionItemHeader.classList.toggle("active");
      currentlyActiveAccordionItemHeader.nextElementSibling.style.maxHeight = 0;
    }

    accordionItemHeader.classList.toggle("active");
    const accordionItemBody = accordionItemHeader.nextElementSibling;
    if(accordionItemHeader.classList.contains("active")) {
      accordionItemBody.style.maxHeight = accordionItemBody.scrollHeight + "px";
    }
    else {
      accordionItemBody.style.maxHeight = 0;
    }
    
  });
});
</script>