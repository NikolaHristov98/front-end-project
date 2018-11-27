---
layout: home
permalink: /contact/
base_url: ../
class: contact
---

<div class="contacts">
    
    <p class="title">Contacts</p>
    <p class="name">Nikola Hristov</p>
    <ul>   
        <li><i class="fas fa-at"></i><p>{{site.email}}</p></li>
         <li><i class="fab fa-github-square"></i><a href="https://github.com/NikolaHristov98"><p>{{site.github_username}}</p></a></li>
    </ul>
</div> 

<div class="contact-form">
    <form action="POST">
        <label for="name">Name:</label>
        <input type="text" id="name">
        <label for="email">Email:</label>
        <input type="text"  id="email">
        <label for="feedback">Your feedback</label>
        <textarea type="text" id="feedvack"></textarea>
    </form>
</div>