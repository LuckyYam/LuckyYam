<div align=center>
    
![Me](https://images.app.goo.gl/YUdetJjuJqYoTKTE8)
### Me ⬆

</div>

## About Me 🎋 

```TypeScript
import { contact, IUser } from './github'

export default class ME implements IUser {
    public static firstName = 'Alen'
    public static lastName = 'Yohannan'
    public static username = 'AlenSaito1'
    public static website = 'https://alenyohannan.xyz'
    public static aliases = ['Ban Takahiro']
    public static skills = [
        'TypeScript', 
        'JavaScript', 
        'NodeJS', 'C', 
        'EJS', 
        'Express', 
        'NoSQL'
    ]
    public static info = {
        age: 17,
        country: 'India',
        org: 'None',
        likes: [
            'TypeScript', 
            'Zelda Series', 
            'JJBA Series', 
            'Well.....'
        ],
        reach: [
            {
                name: contact.Discord,
                username: 'Alen#4688'
            },
            {
                name: contact.WhatsApp,
                url: 'https://wa.me/+919744375687?text=Well...'
            }
        ]
    }
