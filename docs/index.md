## Welcome to PS Frameworks

Sample Codes are organized to here.

### Api Request format

api request format for fasterp

```markdown
//sample api code block
import PsContext from '../context';
const context = useContext(PsContext);
context.psGlobal.apiRequest('v1/admin/upload-image',context.user.mode,form).then((res,error)=>{
                if(res) {
                   //your code here.
                } 
                else{
                    message.error(error);
                } 
               
            });

```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/avkaran/ps-frameworks/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
