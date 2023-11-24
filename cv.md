# Anna Arzamastseva

## Contacts
**Telegram:** AnnaArz
**Email:** a.alekhna@gmail.com.

## Location
Minsk, Belarus.

## About
I'm a pure humanities by education and lifestyle, but I interesting in web development, so I learned html, css and basic JS by myself. Also I know some CMS and worked as freelance web master in different web projects.

## Skills
### Hard Skills
* HTML5, CSS3, SCSS
* Responsive Layout
* Bootstrap Framework 
* CMS Wordpress, Joomla
* JavaScript
* GIT
* SEO
* Photoshop, Illustrator, Figma
and others

### Soft Skills
* Good Teacher
* Good Self Education skill
* Friendly

## Education
* BSU, philology

## Experience
* Freelance Web Master
* IT & Technical specialist in small business
* Teacher for teenagers (HTML, CSS, JS)

## Code Example
```
const getUserInfo = async (userName) => {
    try{
        const response = await fetch(`https://api.github.com/users/${userName}`);
        if(!response.ok){
            throw new Error('Ошибка статус-кода')
        }
        const data = await response.json();
        console.log(data); 
        const {avatar_url, id, login} = data;

        document.body.innerHTML += `<img src="${avatar_url}" alt="${login}"> `;
    } catch (error){
        console.error(error)
    }
}

getUserInfo('it-bear');

```
### English Level
* B1
