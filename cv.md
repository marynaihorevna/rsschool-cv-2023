# Maryna Verbovska

## Frontend Developer

![photo](../photo1.jpg "Пейзаж с горами")

### Contact information:

---

- Contact phone: +380981218919
- E-mail: verbovskaya.freelance@gmail.com
- Telegram: [@maryna_zaitseva](адрес "https://t.me/maryna_zaitseva")
- Linkedn: [@maryna_zaitseva](адрес "https://t.me/maryna_zaitseva")
- Upwork: [](адрес "https://www.upwork.com/freelancers/~0151acd6942c4049d2")

### About myself:

---

Hello, my name is Marina! I am a certified marketer with programming skills. I can do:

- one-page website
- business card website
- online store
- corporate website.

Hope for long-term cooperation! I will be happy to make a website that you will be satisfied with!

### Skills and Proficiency:

---

| Hard skills:             |   Soft skills   |
| ------------------------ | :-------------: |
| HTML AND CSS             |     Empathy     |
| Bootstrap                |  Communication  |
| Responsive/mobile design |    Ambition     |
| Javascript               | Industriousness |
| Adobe Photoshop, Figma   |    Teamwork     |

### Code example:

---

#### Task: create Tabs

```
window.addEventListener('DOMContentLoaded', () => {
    const   tabs = document.querySelectorAll('.tabheader__item'),
            contentTabs = document.querySelectorAll('.tabcontent'),
            parentTabs = document.querySelector('.tabheader__items');

    function hideContentTab() {
        ContentTabs.forEach(item => {
            item.style.display = 'none';
        });

        tabs.forEach(item => {
            item.classList.remove('tabheader__item_active');
        });
    }

    function showTabContent(i = 0) {
        contentTabs[i].style.display = 'block';
        tabs[i].classList.add('tabheader__item_active');
    }

    hideContentTab();
    showTabContent(0);

    tabsParent.addEventListener('click', (event) => {
        const target = event.target;

        if(target && target.classList.contains('tabheader__item')) {
            tabs.forEach((item, i) => {
                if(target == item) {
                    hideContentTab();
                    showTabContent(i);
                }
            });
        }
    });

```

### Skills and Proficiency:

---

- Epam for Switchers (Frontend)
- WayUp "Web Development"
- WayUp "Javascript"
- Course I. Petrichenko "Web Development"(in progress)
- Course I. Petrichenko "Javascript/React"(in progress)
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

### Languages:

---

- Russian (native);
- Ukrainian (native);
- English (B1);
- German (A2);
