![Alt-Dzmitry Salata photo](assets/img/Photo.png)      
#DZMITRY SALATA                                 
__С# DEVELOPER__                                
                                                
__DATE OF BIRTH: 23.08.1990__                   

###PERSONAL PROFILE                             
I want to acquire new skills and experience.    
Professional growth and learning are vital 
for me. 
I want to change the area, and I have a strong
desire for IT.

I'm looking for an IT company in which I would
like to gain my first commercial
experience in development.

###SKILLS
* Knowledge of C#;
* Knowledge of HTML, CSS, JS (React);
* Knowledge of OOP principles and design patterns;
* GIT knowledge;
* English - A2. Able to read technical documentation and write a business
letter;
* Making a good cappuccino;

###WORK EXPERIENCE
__Engineer (Engineering Department)__

Belarusian International Airlines Belavia, 01 August 2013 - 01 April 2019;

Aviation documents development;

__Maintenance technician Mechanic B1 (Base Maintenance Department)__

Belarusian International Airlines Belavia, 01 APRIL 2019 - PRESENT;

Aircraft maintenance;

###CONTACTS
Phone +375 (29) 383-40-62;

Email: salata.dzmitry@gmail.com;

Address: st. Zudro 28, Minsk, Republic of Belarus;

Discord nick in rs-school: Dmitry Salata (@Geek-Dmitry)

###EDUCATION AND TRAINING
__Belarusian state academy of aviation__

01 September 2008 - 30 January 2014;

Engineer;

__TEACHMESKILLS__

2021;

FullStack C# developer;

###CODE EXAMPLE

C# EXAMPLE:
```
public abstract class BaseRepository<ModelType> 
        : IBaseRepository<ModelType> where ModelType : BaseModel
    {
        protected SpaceDbContext _spaceDbContext;
        protected DbSet<ModelType> _dbSet;

        public BaseRepository(SpaceDbContext spaceDbContext)
        {
            _spaceDbContext = spaceDbContext;
            _dbSet = _spaceDbContext.Set<ModelType>();
        }

        public virtual List<ModelType> GetAll()
        {
            return _dbSet.ToList();
        }
```
[__Link on file from example on GITHUB__](https://github.com/JinOptimist/RocketIsSpace/blob/master/TMS.Net07.Lesson1/SpaceWeb/EfStuff/Repositories/BaseRepository.csl "GITHUB link")

HTML EXAMPLE:

```html
 <div class="header-lower">
  <nav class="header-lower-nav">
    <ul class="header-lower-nav-list">
      <li class="header-lower-nav-item">
        <a href="" class="header-lower-nav-link">О нас</a>
      </li>
      <li class="header-lower-nav-item">
        <a href="" class="header-lower-nav-link">Услуги</a>
      </li>
      <li class="header-lower-nav-item">
        <a href="" class="header-lower-nav-link">Преимущества</a>
      </li>
      <li class="header-lower-nav-item">
        <a href="" class="header-lower-nav-link">Размещение</a>
      </li>
      <li class="header-lower-nav-item">
        <a href="" class="header-lower-nav-link">Блог</a>
      </li>
      <li class="header-lower-nav-item">
        <a href="" class="header-lower-nav-link">Контакты</a>
      </li>
    </ul>
```
[__Link on file from example on GITHUB__](https://github.com/Geek-Dmitry/Hotel_Website/blob/main/index.html "GITHUB link")

CSS EXAMPLE:
```css
.header-lower {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 14px 45px;
  background-color: #FFFFFF;
  border-radius: 15px;
}

.header-lower-nav-list {
  display: flex;
}

.header-lower-nav-item {
  word-break: break-word;
}

.header-lower-nav-item:not(:last-child) {
  margin-right: 45px;
}

.header-lower-nav-link {
  font-family: 'Mulish', sans-serif;
  font-style: normal;
  font-size: 16px;
  line-height: 16px;
  color: #666666;
}
```

[__Link on file from example on GITHUB__](https://github.com/Geek-Dmitry/Hotel_Website/blob/main/css/style.css "GITHUB link")

JS EXAMPLE:
```javascript
$(document).ready(function () {
    $(".spoiler__title").click(function(event) {
        
        if ($(".spoiler").hasClass("one")) {
            $(".spoiler__title").not($(this)).removeClass("active");
            $(".spoiler__description").not($(this).next()).slideUp(200);
        }

        $(this).toggleClass("active").next(".spoiler__description").slideToggle(200);
    });
});
```

[__Link on file from example on GITHUB__](https://github.com/Geek-Dmitry/ClothesStoreWebsite/blob/main/ClothesStoreWebsite/wwwroot/js/product.js "GITHUB link")

###ADDITIONAL INFORMATION

[__GIT Link__](https://github.com/Geek-Dmitry "GITHUB link")  

[__CodeWars Link__](https://www.codewars.com/users/Kendaro "CodeWars link")