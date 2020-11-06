## Daniil Yandybaev
### Contact Info
- __Email__: xramirezx@outlook.com
- __WhatsApp__: [+7 (937) 256-65-80](tel:89372566580)
- __VK__: [@icefleen](https://vk.com/icefleen)
- __Telegram__: [@icefleen](https://t.me/icefleen)

### Summary
I used to create __chat bots__ in VK and Telegram, __VK Mini Apps__,
some small __SPAs__ (Single Page Applications) and now I want to become a strong front-end engineer. I can say about myself that I'm a fast learner, responsible and stress-resistant.

### Skills
##### Frontend
- __HTML/CSS/JavaScript__ - _three_ years
- __SASS/SCSS__ - _two_ months
- __Bootstrap 4__ - _two_ years
- __VueJS, Vuex, Vue Router__ - _one_ year
- __React, Redux, React Router__ - _three_ months
- Other tools such as __JSX__, __JQuery__, __NPM__, __Pug__, __Stylus__ and etc.
##### Other skills
- __Python__ - _four_ years
- __Flask__ - _six_ months
- __NodeJS, Express__ - _two_ months
- __C__/__C++__, __C#__, __Java__, __Kotlin__, __PHP__, __Lua__, __Transact SQL__, __Mongo DB__

### Code examples
```JavaScript
// Light example of my React component using VKUI

import {FormLayout, FormLayoutGroup, Input, Card, Select, Group, Cell, Header} from "@vkontakte/vkui";
import React from 'react';

const GuestCard = ({guest, index, changeGuestInfo, sum}) => {

    return (
        <Card size="m" mode="shadow" className="my-1" key={index}>
            <Group>
                <Header className="mb-0">Гость {index + 1}</Header>
                <FormLayout>
                    <FormLayoutGroup top="Время прибытия">
                        <Input type="time" value={guest.timeIn} name="guestTimeIn" onChange={changeGuestInfo.bind(this, index)} />
                    </FormLayoutGroup>
                    <FormLayoutGroup top="Время убытия">
                        <Input type="time" value={guest.timeOut} name="guestTimeOut" onChange={changeGuestInfo.bind(this, index)} />
                    </FormLayoutGroup>
                    <FormLayoutGroup top="Скидка">
                        <Select value={guest.discount} name="guestDiscount" onChange={changeGuestInfo.bind(this, index)}>
                            <option value="0">Нет</option>
                            <option value="1">Постоянный посетитель 15%</option>
                            <option value="2">Прогульщик 25%</option>
                            <option value="3">Молодежная карта СГУ 15%</option>
                            <option value="4">День рождения 15%</option>
                        </Select>
                    </FormLayoutGroup>
                    <FormLayoutGroup top="Сертификат, минуты">
                        <Input type="number" min="0" value={guest.cert} name="guestCert" onChange={changeGuestInfo.bind(this, index)} placeholder="0"/>
                    </FormLayoutGroup>
                </FormLayout>
                <Cell>Итого: {sum} руб.</Cell>
            </Group>
        </Card>
    )
}

export default GuestCard;
```

### Experience 
[My biggest work with React, react-router, redux, react-redux, redux-form and others](https://github.com/icefleen/social-nerwork)


### Education
[Yuri Gagarin State Technical University Of Saratov](http://en.sstu.ru) / [Саратовский государственный университет им. Гагарина Ю. А.](http://www.sstu.ru/)  
Pending Bachelor’s degree (third course)

### English
Pre-intermediate
