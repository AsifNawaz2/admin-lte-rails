# Admin-lte Rails


**Ruby version** 3.1.2

**Rails version** 7.0.4

## Steps followed for project

#### 1. Run ```rails new assessment -j esbuild --css bootstrap -d postgresql```
#### 2. To make it compatable with admin-lte 3.2 run
   * ```yarn remove bootstrap```

   * ```yarn add bootstrap@4.6```

#### 3. Add this to app/assets/stylesheets/application.bootstrap.scss
```@import 'admin-lte/dist/css/adminlte.css'```

#### 4. Add this to app/javascript/application.js
```import 'admin-lte/dist/js/adminlte.js'```

### 5. All good to go
run ```bin/dev```
