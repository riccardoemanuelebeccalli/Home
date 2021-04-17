#Welcome to my site

My name is Riccardo Emanuele Beccalli and I am a Physics student at the [University of Milan](https://www.fisica.unimi.it/)

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/riccardoemanuelebeccalli/Site/edit/main/README.md) to maintain and preview the content for your website in Markdown files, ciao. **Sono il capo**

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block
#include <iostream>
#include <iomanip>
#include <fstream>
#include <cstring>
using namespace std;

int scrivo_testo () {
  	ofstream myfile;  // default ios::out
  	double x, y, z;
  	int i = 0;
  	myfile.open ("esercizio1.txt");
  	if (myfile.is_open())
    	{
    		do
    		{
	    		cout << "Inserisci x, y e z>\n";
    			cin >> x;
    			cin >> y;
    			cin >> z;
    		
    			myfile << setprecision(4) << x << setw(8) << y << setw(12) << z << endl;
    			i ++;
    		}while(i < 5);
    
    		myfile.close();
    	}
  	cout << "ok: ho scritto il file\n";
  	return 0;
}

int main()
{
	scrivo_testo();
}

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/riccardoemanuelebeccalli/Site/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
