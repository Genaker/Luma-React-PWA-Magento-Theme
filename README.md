# Luma-React-PWA-Magento-Theme

<img src="https://raw.githubusercontent.com/Genaker/Luma-React-PWA-Magento-Theme/master/web/images/logo.jpeg" alt="Magento React Theme"/>

Blazing-Fast Default Magento Luma theme on ReactJS UI components PWA features with better front performance.

Luma react Open Source Theme aim to resolve the performance issues by removing all the awfull introduced by Adobe Magento 2 based themes and starting with a blank html. The thousands of bloated junk JavaScript files libraries are replaced with no JS framework known as Vanila JS but you can add any JS framework additionally for your needs ReactJS, Vue.Js,  Alpine.js. In addition, all CSS is optimised and not replaced. so you can basicaly convert your existed Magento junk theme to a fast theme.
# Performace improvements
After the Consultation with Erwin Hofman 

We made big improvements in the LCP metrics on Mobile. Now this theme even faster than before.

![image](https://user-images.githubusercontent.com/9213670/153733227-56f839b8-42bc-4b4c-986d-c98ea916cbca.png)

You can check Google Page Speed results here:

https://pagespeed.web.dev/report?url=https%3A%2F%2Freact-luma.merche.io%2Ffusion-backpack.html

# Installation 
```
 composer require genaker/theme-react-luma --ignore-platform-reqs
 mysql -e "select * from theme"
 bin/magento config:set --scope="default" "design/theme/theme_id" 4 #whatever id you have
```
or go to admin : 

Content -> Design -> Configuration

Apply theme:

![image](https://user-images.githubusercontent.com/9213670/154371384-2abd5712-380e-44ad-8e67-b259eb2d6f42.png)

Theme info:
![image](https://user-images.githubusercontent.com/9213670/154369973-b36f8110-fdfc-4f03-9f1b-9891e0a6cb9d.png)

clear the cache. 

# Donation 
Magento 2 Super Fast Rect Luma them is free and Open Source comparing to other paid solutions. 

You can donate to support our contributors: 

https://paypal.me/magentasoftware?country.x=US&locale.x=en_US

# Dependencies:

Magento React Theme uses Magento React integration extension (https://github.com/Genaker/reactmagento2/) as a dependency. Extension will be added automaticaly if to install via Composer.

For the best performace You shuld use:
* CSS optimiser tool: (not publicly available)
* Improved Magento FPC: (not publicly available)
* Magento Mictoservices: Laragento/Laragento, PyGento/Python3, NodeJento/NodeJS
* Magento Opcache React GUI: https://github.com/Genaker/Magento2OPcacheGUI
* PWA Magento Extension:https://github.com/Genaker/Magento2PWA
* Magento Open Source Terraform AWS Cloud: https://github.com/Genaker/TerraformMagentoCloud
