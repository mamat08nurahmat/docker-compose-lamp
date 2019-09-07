###################
CiCOOL
###################

**ISSUE access**
sudo chmod 777 -R www/

**ISSUE session**
application/config/config.php
// $config['sess_save_path'] = NULL;
$config['sess_save_path'] = sys_get_temp_dir();

**ISSUE mysql**
set global sql_mode='STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION';

set session sql_mode='STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION';


**Feature**
- Wizzard setup
- CRUD Generator
- Auto generate Web API
- Full Authentication easy to custom Auth
- Form Builder
- HTML Page Builder
- Admin LTE Themes

**Library**
- template library : https://github.com/philsturgeon/codeigniter-template
- codeiginter auth : https://github.com/emreakay/CodeIgniter-Aauth
- fine uploader : http://fineuploader.com/
- toastr : https://github.com/CodeSeven/toastr
- hotkeys : https://github.com/jeresig/jquery.hotkeys
- icon : http://freedesignfile.com/104497-creative-file-format-icons-vector-graphics/
- json view : https://github.com/ridwanskaterock/jquery-jsonview
- jquery address map picker : https://github.com/bygiro/jQuery-AddressPicker-ByGiro/
- jquery touch pouch : http://touchpunch.furf.com/
- Jquery spectrum : https://github.com/bgrins/spectrum
- Medium editor : https://github.com/yabwe/medium-editor

**change log**

v2.0.0
- setting for default landing from page
- fix bug loader on nginx
- multiple file upload crud builder
- add validation max item for multiple file
- responsive table
- export data to PDF
- example chart