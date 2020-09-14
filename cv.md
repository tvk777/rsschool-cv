## Tatyana Klimenko

### Contacts
- __City__: Dnipro, Ukraine
- __Email__: klimenko.tv7@gmail.com
- __Web-site__: [sdb-studio.com](https://sdb-studio.com/)

### Summary
Hi! I'm Tatyana. I have been working in web development for almost 10 years now. I really love to learn new technologies and new programming languages. Now I work as a web developer in the SDB web-studio.

### Skills
* Web Technologies
  * Html5
  * Css3
* Programming Languages & Data Bases
  * PHP
  * MySql
  * Javascript
* Frameworks & Libraries
  * Yii2
  * Jquery
  * Bootstrap
  * React
* CMS
  * Joomla
  * Wordpress
  * PrestaShop
  * Opencart  
* Version Control 
  * Git
* IDE:
  * VS Code
  * PhpStorm
  * WebStorm 

### Code samples
__React__
``` react
let mapStateToProps = (state) => {
    return {
        dialogsPage: state.dialogsPage
    }
}
let mapDispatchToProps = (dispatch) => {
    return {
        sendMessage: () => {
            dispatch(sendMessageCreator());
        },
        updateNewMessageBody: (body) => {
            dispatch(updateNewMessageBodyCreator(body));
        }
    }
}
export default compose(
    connect(mapStateToProps, mapDispatchToProps),
    withAuthRedirect
)(Dialogs);
```
__PHP__
```
public function getSlides()
    {
        $slides = [];
        if (count($this->images) > 0) {
            foreach ($this->images as $i => $img) {
                $slides[$i]['thumb'] = $img->thumb300x200Src;
                $slides[$i]['big'] = $img->imgSrc;
            }
        }
        return $slides;
    }
```

### My Projects
##### [SDB Web-Studio Site](https://sdb-studio.com/)
##### [Budapest Online Store](https://budapesht.com.ua/)
##### [Bestcollection Online Store](http://bestcollection.com.ua/)

### Education
Oles Honchar Dnipro National University Faculty of Physics, Electronics and Computer Sciences

### English
Pre-intermediate  