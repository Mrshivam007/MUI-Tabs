# React-Tutorial

(https://www.freecodecamp.org/news/content/images/2021/06/Ekran-Resmi-2019-11-18-18.08.13.png)

## Getting Started With React 👾
Step 1:
```
npm create-react-app my-react
```

Step 2:
```
cd my-react
```

Step 3:
```
npm start
```

## Getting Started with [Bootstrap](https://getbootstrap.com/docs/5.2/getting-started/introduction/)
Adding CSS:
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
```

Adding JS:
```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
```

Adding Navbar:
```
 <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
            </ul>
          </div>
        </div>
        <AccessibilityNewIcon sx={{ marginRight: "82rem" }} color="primary" />
      </nav>
```

Adding Cards:

To use cards go to [Bootstrap Cards](https://getbootstrap.com/docs/5.2/components/card/)

## Getting Started with [React-Routers](https://reactrouter.com/en/main/start/tutorial)
Starter Code:
```
npm install react-router-dom
```

### In App.js:
Import Items
```
import {BrowserRouter, Route, Routes} from 'react-router-dom';
```

Adding Components and Pages
```
 <BrowserRouter>
<Header />   

     <Routes>
      <Route path='/' element={<Home />}></Route>
     <Route path='/home' element={<Home />}></Route>
     </Routes>
   
    </BrowserRouter>
```

### In Header.jsx
Import
```
import {Link} from 'react-router-dom';
```

Adding Link
```
<Link  to="/home">Home</Link>
```
        or
```
<Link to='/home' class="btn btn-primary" role="button">Home</Link>
```


## Getting Started with [MUI](https://mui.com/)
Starter Code:
```
npm install @mui/material @emotion/react @emotion/styled
```

### [Icons](https://mui.com/material-ui/material-icons/)

Adding Icons-Material
```
npm install @mui/icons-material
```

Adding Icons

```
import AccessAlarmIcon from '@mui/icons-material/AccessAlarm';
import ThreeDRotation from '@mui/icons-material/ThreeDRotation';
```
        or
```
import { AccessAlarm, ThreeDRotation } from '@mui/icons-material';
```

Adding Icons Color
```
<HomeIcon />
<HomeIcon color="primary" />
<HomeIcon color="secondary" />
<HomeIcon color="success" />
<HomeIcon color="action" />
<HomeIcon color="disabled" />
<HomeIcon sx={{ color: pink[500] }} />
```

Adding Icons Size
```
<HomeIcon fontSize="small" />
<HomeIcon />
<HomeIcon fontSize="large" />
<HomeIcon sx={{ fontSize: 40 }} />
```

### For more styling Icons 
[Icons Material](https://mui.com/material-ui/icons/)








