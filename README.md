# python
Searching corrupted images from a website 


from os import listdir
from PIL import Image

filename= 
   
for filename in listdir('./'):
  if filename.endswith('.png'):
    print(filename)

try:
    img = Image.open('./'+filename) # open the image file
    img.verify()
       # These next functions may produce an exception
  # <some function>
except (IOError, SyntaxError) as e:
    print('Bad file:', filename) 
     # These are the exceptions we're looking for
  # <do something... like print an intelligent error message>



Website 

  <!DOCTYPE html>
<html>
 <head>
  <meta content="width=device-width" name="viewport"/>
  <meta charset="utf-8"/>
  <title>
   DocMZ
  </title>
  <link href="/favicon.png" rel="icon"/>
  <meta content="4" name="next-head-count"/>
  <link as="style" href="/_next/static/css/styles.a1eab998.chunk.css" rel="preload"/>
  <link data-n-g="" href="/_next/static/css/styles.a1eab998.chunk.css" rel="stylesheet"/>
  <link as="style" href="/_next/static/css/e8ba0c2e.8db9f8a7.chunk.css" rel="preload"/>
  <link data-n-p="" href="/_next/static/css/e8ba0c2e.8db9f8a7.chunk.css" rel="stylesheet"/>
  <link as="style" href="/_next/static/css/0192d2e8.19432dbc.chunk.css" rel="preload"/>
  <link data-n-p="" href="/_next/static/css/0192d2e8.19432dbc.chunk.css" rel="stylesheet"/>
  <link as="style" href="/_next/static/css/pages/index.cd071838.chunk.css" rel="preload"/>
  <link data-n-p="" href="/_next/static/css/pages/index.cd071838.chunk.css" rel="stylesheet"/>
  <noscript data-n-css="">
  </noscript>
  <link as="script" href="/_next/static/chunks/main-4e473b9358c28967fe67.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/webpack-aa403ce22e7aa0f354a1.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/framework.9fac7f60fdab795c24b8.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/cb1608f2.214663374522c8133134.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/75fc9c18.3e98bfd3653aed98df31.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/c86bb9a13864c97f4306d913b048d33e5d5628d7.d18b4cd5b9181f9df943.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/74997e99a3c5579caa2526e643d07fdbe156f62a.63bbb1a691a67ad33892.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/8aaefd24f6f471bcbddabb77ab483e809e275136.5a7d5f6f703692ea45f7.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/facd1ce66b42c18d3ee0f82ff803869cdff053df.9cfb233302fd661d19f9.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/9316a9feb24c5fc2c3f0aca9d93e100958f01eea.9952b0f8b7458ffbbdb9.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/002968e393e8c362597a6ffa918175194da586b6.999180cea4c6dc63131a.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/9ccc6e9a634ba6baae5b9bd3e51fb19f54e9a475.2982fe347b6c5794f4fe.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/1cb35f83e3404dc4e6c84c5c5f921b669fb7e1c9.0046728c71b6d6812323.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/c5dffeb90389c2d9d1ac64562a1a0c99ed325eb6.f6b2ff75076110131392.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/d15eab43bd30afb504a379ed209248cd3b4424cc.232a3d4c1105df92b496.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/a58409a16ca686574b149cb479cf9fae29db4027.c42310e3f3fe5355cc17.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/769993294b8f26110af2d0cafd87dba2e21939a0.2317aa61d36d98841d89.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/a97250b3cfd0241b16b47e1dd492fc33d76a869e.8bb3981cf392388cab41.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/ed42cf7cf4d127e28552aadc35e8384aa12e28c0.995b092053cbb134e175.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/2ad07823fd0ff8e9927ad17ef9337ddb1c92874c.471d6a87d0140aa19863.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/a20acd79148e99ca0424198d55a4e79070ed5d14.404cccb54f906c78322b.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/4822ecf71173a1d5d7545ee9312862fc5a4bfdf9.da33bdc577eb2eea01d6.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/59e023516f59ba2e6b1398e1d76344ed99e0f753.5de2c34f835d86e0dec1.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/e342705b3d0a23ab9db5c7cc876ac85177470104.8961cc40d5e29d1fc363.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/5825a58d163fd35f82e8d62eb2f8b239e5976d79.da4ff91fac4f409fa468.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/9d2e1ff9cc29387a0f12fc618b337bc50e1f1a08.b3c7fb29882e45a17159.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/styles.7dba968fc7c24df8bf27.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/pages/_app-38271f4f0af08c94ee77.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/79de5ff0.8553f0c9b32a5fb259e8.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/e8ba0c2e.5cce01f8b620a635bfe5.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/0192d2e8.f670b774c84bedcb2ff7.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/774383da.96a3f147dc1d4115bb99.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/46751129.8a4e5d9d6351c8c812e0.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/1a171660c3ba2a502c14fa6f6c6862c486f0235a.57e39ee8f9e99914d1f0.js" rel="preload"/>
  <link as="script" href="/_next/static/chunks/pages/index-fd0a25e04d5b97de951c.js" rel="preload"/>
 </head>
 <body>
  <div id="__next">
   <div class="c-layout c-layout--basic">
    <script async="" defer="" src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBXxXfKy5wtHEO9XniOvGEKPME-_ldClVk&amp;libraries=places">
    </script>
    <div>
     <header>
      <section id="header">
       <div class="scrollable-header-scrolled">
        <nav class="container-fluid navbar navbar-expand-lg navbar-light">
         <button class="ant-btn main-drawer-opener" style="border:none;box-shadow:none;background:transparent" type="button">
          <svg aria-hidden="true" class="svg-inline--fa fa-bars fa-w-14" data-icon="bars" data-prefix="fas" focusable="false" role="img" viewbox="0 0 448 512" xmlns="http://www.w3.org/2000/svg">
           <path d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z" fill="currentColor">
           </path>
          </svg>
         </button>
         <span class="navbar-brand" style="cursor:pointer">
          <img alt="Docmz Logo" src="/images/docmz-logo.svg"/>
         </span>
         <button aria-controls="basic-navbar-nav" aria-label="Toggle navigation" class="navbar-toggler collapsed" type="button">
          <span>
           <svg aria-hidden="true" class="svg-inline--fa fa-bars fa-w-14" data-icon="bars" data-prefix="fas" focusable="false" role="img" viewbox="0 0 448 512" xmlns="http://www.w3.org/2000/svg">
            <path d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z" fill="currentColor">
            </path>
           </svg>
          </span>
         </button>
         <div class="navbar-collapse collapse" id="basic-navbar-nav">
          <div class="ml-auto navbar-nav">
           <a class="nav-link" href="#" role="button">
            <a href="/help">
             Help
            </a>
           </a>
           <div class="dropdown nav-item">
            <a aria-expanded="false" aria-haspopup="true" class="dropdown-toggle nav-link" href="#" id="basic-nav-dropdown" role="button">
             Login
            </a>
           </div>
          </div>
         </div>
        </nav>
       </div>
      </section>
     </header>
     <main class="main-wrapper" role="main">
      <div class="maincontent-wrapper">
       <section class="section" id="hero-section">
        <div class="container">
         <div class="header">
          <h1>
           Better and more accessible healthcare
          </h1>
          <p>
           Now available at your fingertips
          </p>
         </div>
         <div class="row mt-5 mb-4 search-section">
          <div class="col-12">
           <div class="ant-select ant-select-auto-complete card ant-select-single ant-select-customize-input ant-select-show-search">
            <div class="ant-select-selector">
             <span class="ant-select-selection-search">
              <span class="ant-input-group-wrapper ant-input-group-wrapper-lg ant-input-search ant-input-search-large ant-select-selection-search-input">
               <span class="ant-input-wrapper ant-input-group">
                <input aria-activedescendant="undefined_list_0" aria-autocomplete="list" aria-controls="undefined_list" aria-haspopup="listbox" aria-owns="undefined_list" autocomplete="off" class="ant-input ant-input-lg" placeholder="Search doctors" role="combobox" type="search" value=""/>
                <span class="ant-input-group-addon">
                 <button class="ant-btn ant-btn-lg ant-btn-icon-only ant-input-search-button" type="button">
                  <span aria-label="search" class="anticon anticon-search" role="img">
                   <svg aria-hidden="true" data-icon="search" fill="currentColor" focusable="false" height="1em" viewbox="64 64 896 896" width="1em">
                    <path d="M909.6 854.5L649.9 594.8C690.2 542.7 712 479 712 412c0-80.2-31.3-155.4-87.9-212.1-56.6-56.7-132-87.9-212.1-87.9s-155.5 31.3-212.1 87.9C143.2 256.5 112 331.8 112 412c0 80.1 31.3 155.5 87.9 212.1C256.5 680.8 331.8 712 412 712c67 0 130.6-21.8 182.7-62l259.7 259.6a8.2 8.2 0 0011.6 0l43.6-43.5a8.2 8.2 0 000-11.6zM570.4 570.4C528 612.7 471.8 636 412 636s-116-23.3-158.4-65.6C211.3 528 188 471.8 188 412s23.3-116.1 65.6-158.4C296 211.3 352.2 188 412 188s116.1 23.2 158.4 65.6S636 352.2 636 412s-23.3 116.1-65.6 158.4z">
                    </path>
                   </svg>
                  </span>
                 </button>
                </span>
               </span>
              </span>
             </span>
             <span class="ant-select-selection-placeholder">
             </span>
            </div>
           </div>
          </div>
         </div>
         <div class="menu-list">
          <span class="menu-li" style="cursor:pointer;font-weight:600">
           Doctors
          </span>
          <span class="menu-vr">
           |
          </span>
          <span class="menu-li" style="cursor:pointer">
           Clinics
          </span>
         </div>
        </div>
       </section>
       <section class="section" id="healthcare-products">
        <div class="container">
         <div class="header">
          <h1>
           Modern healthcare for all your needs!
          </h1>
          <p>
           Whatever healthcare related issue you have, DocEz is here to help.
          </p>
         </div>
         <div class="carousel">
         </div>
        </div>
       </section>
       <section class="section" id="story-section">
        <div class="container">
         <div class="row">
          <div class="col-md-6">
           <div class="d-flex align-items-end header">
            <h1>
             the story of
             <span class="greeny_blue">
              <!-- -->
              DocEz
             </span>
             ,
             <!-- -->
             begins With trust
             <!-- -->
             .
            </h1>
           </div>
          </div>
          <div class="col-md-6">
           <p>
            Like every strong relationship, ours with you will be built on the foundation of trust. It is of utmost importance to us that your privacy is ensured. Your medical records will be available only to the Doctor you choose to share them with. We do not store, process or profit off of your data and assure you that is how it is always going to be.
            <br/>
            <br/>
            DocEz cares about your wellbeing and understands that your privacy is an important part of your wellbeing. You can completely relax and get all the medical help that you need, secure in the knowledge that we will never let you down.
            <br/>
            <br/>
           </p>
          </div>
         </div>
        </div>
       </section>
       <section class="section" id="how-section">
        <div class="container">
         <div class="header">
          How
          <!-- -->
          <span class="primary">
           <!-- -->
           DocEz
          </span>
          <!-- -->
          works
         </div>
         <div class="ant-row ant-row-center">
          <div class="ant-col ant-col-12 ant-col-xs-24 ant-col-md-12">
           <div id="mobileDiv">
            <img id="mobileOutline" src="/images/home/mobile_outline.png" width="250"/>
            <img id="mobileContent" src="https://fsa.zobj.net/crop.php?r=TyNPh-taEXT5LPy2LY7NcnqFgmCq202lgD6HIp1SXIh0UU2v8FLhod6S8ePxyMWNVr0WGpLVK2IjlFRhSUMnC3-JY2b_nNSlwAIMQCkBoMgPeHg2TRfXL5IpQ8eJbx684zh68xhrnhvubPS0hNvajNzYs8Lr9wXQcYZRLb_3_vAEzqKup4hl7gjojcY" width="200"/>
           </div>
          </div>
          <div class="ant-col ant-col-12 d-flex ant-col-xs-24 ant-col-md-12">
           <div class="f-end">
            <div class="subheader">
             Create your account
            </div>
            <p>
             Let us get to know you so that we can connect you to a healthcare option of your choosing.
            </p>
            <div class="ant-row stepper">
             <div class="ant-col ant-col-6 step active">
             </div>
             <div class="ant-col ant-col-6 step inactive">
             </div>
             <div class="ant-col ant-col-6 step inactive">
             </div>
            </div>
           </div>
          </div>
         </div>
        </div>
       </section>
       <div class="section4a">
       </div>
       <section class="section" id="stats-section">
        <div class="container">
         <div class="row">
          <div class="col-sm-4">
           <center>
            <div class="number">
             <div>
              5
             </div>
            </div>
            <div class="large-number">
             million
            </div>
            <div class="text">
             Vivamus eget aliquam dui.
            </div>
           </center>
          </div>
          <div class="col-sm-4">
           <center>
            <div class="number">
             <div>
              46
             </div>
            </div>
            <div class="large-number">
             million
            </div>
            <div class="text">
             Vivamus eget aliquam dui.
            </div>
           </center>
          </div>
          <div class="col-sm-4">
           <center>
            <div class="number">
             <div>
              2
             </div>
            </div>
            <div class="large-number">
             million
            </div>
            <div class="text">
             Vivamus eget aliquam dui.
            </div>
           </center>
          </div>
         </div>
        </div>
       </section>
       <section class="section" id="about-us">
        <div class="container">
         <div class="header">
          An easy way to find the best healthcare near you
         </div>
         <div class="text">
          You can now search for medical practitioners and hospitals near you from the comfort of your home. You can book an appointment and even consult a doctor via DocEz. What�s more? DocEz even lets you order your medicines. It is one stop shop for all your healthcare related problems.
         </div>
         <div class="d-flex flex-wrap">
          <div class="mx-auto">
           <div class="row">
            <div class="features">
             <div class="icon">
              <svg aria-hidden="true" class="svg-inline--fa fa-window-restore fa-w-16" data-icon="window-restore" data-prefix="fas" focusable="false" role="img" viewbox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
               <path d="M512 48v288c0 26.5-21.5 48-48 48h-48V176c0-44.1-35.9-80-80-80H128V48c0-26.5 21.5-48 48-48h288c26.5 0 48 21.5 48 48zM384 176v288c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V176c0-26.5 21.5-48 48-48h288c26.5 0 48 21.5 48 48zm-68 28c0-6.6-5.4-12-12-12H76c-6.6 0-12 5.4-12 12v52h252v-52z" fill="currentColor">
               </path>
              </svg>
             </div>
             <div class="content">
              <p>
               Vivamus eget aliquam dui.
              </p>
             </div>
            </div>
            <div class="features">
             <div class="icon">
              <svg aria-hidden="true" class="svg-inline--fa fa-futbol fa-w-16" data-icon="futbol" data-prefix="fas" focusable="false" role="img" viewbox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
               <path d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zm-48 0l-.003-.282-26.064 22.741-62.679-58.5 16.454-84.355 34.303 3.072c-24.889-34.216-60.004-60.089-100.709-73.141l13.651 31.939L256 139l-74.953-41.525 13.651-31.939c-40.631 13.028-75.78 38.87-100.709 73.141l34.565-3.073 16.192 84.355-62.678 58.5-26.064-22.741-.003.282c0 43.015 13.497 83.952 38.472 117.991l7.704-33.897 85.138 10.447 36.301 77.826-29.902 17.786c40.202 13.122 84.29 13.148 124.572 0l-29.902-17.786 36.301-77.826 85.138-10.447 7.704 33.897C442.503 339.952 456 299.015 456 256zm-248.102 69.571l-29.894-91.312L256 177.732l77.996 56.527-29.622 91.312h-96.476z" fill="currentColor">
               </path>
              </svg>
             </div>
             <div class="content">
              <p>
               Vivamus eget aliquam dui.
              </p>
             </div>
            </div>
            <div class="features">
             <div class="icon">
              <svg aria-hidden="true" class="svg-inline--fa fa-address-book fa-w-14" data-icon="address-book" data-prefix="fas" focusable="false" role="img" viewbox="0 0 448 512" xmlns="http://www.w3.org/2000/svg">
               <path d="M436 160c6.6 0 12-5.4 12-12v-40c0-6.6-5.4-12-12-12h-20V48c0-26.5-21.5-48-48-48H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h320c26.5 0 48-21.5 48-48v-48h20c6.6 0 12-5.4 12-12v-40c0-6.6-5.4-12-12-12h-20v-64h20c6.6 0 12-5.4 12-12v-40c0-6.6-5.4-12-12-12h-20v-64h20zm-228-32c35.3 0 64 28.7 64 64s-28.7 64-64 64-64-28.7-64-64 28.7-64 64-64zm112 236.8c0 10.6-10 19.2-22.4 19.2H118.4C106 384 96 375.4 96 364.8v-19.2c0-31.8 30.1-57.6 67.2-57.6h5c12.3 5.1 25.7 8 39.8 8s27.6-2.9 39.8-8h5c37.1 0 67.2 25.8 67.2 57.6v19.2z" fill="currentColor">
               </path>
              </svg>
             </div>
             <div class="content">
              <p>
               Vivamus eget aliquam dui.
              </p>
             </div>
            </div>
            <div class="features">
             <div class="icon">
              <svg aria-hidden="true" class="svg-inline--fa fa-anchor fa-w-18" data-icon="anchor" data-prefix="fas" focusable="false" role="img" viewbox="0 0 576 512" xmlns="http://www.w3.org/2000/svg">
               <path d="M12.971 352h32.394C67.172 454.735 181.944 512 288 512c106.229 0 220.853-57.38 242.635-160h32.394c10.691 0 16.045-12.926 8.485-20.485l-67.029-67.029c-4.686-4.686-12.284-4.686-16.971 0l-67.029 67.029c-7.56 7.56-2.206 20.485 8.485 20.485h35.146c-20.29 54.317-84.963 86.588-144.117 94.015V256h52c6.627 0 12-5.373 12-12v-40c0-6.627-5.373-12-12-12h-52v-5.47c37.281-13.178 63.995-48.725 64-90.518C384.005 43.772 341.605.738 289.37.01 235.723-.739 192 42.525 192 96c0 41.798 26.716 77.35 64 90.53V192h-52c-6.627 0-12 5.373-12 12v40c0 6.627 5.373 12 12 12h52v190.015c-58.936-7.399-123.82-39.679-144.117-94.015h35.146c10.691 0 16.045-12.926 8.485-20.485l-67.029-67.029c-4.686-4.686-12.284-4.686-16.971 0L4.485 331.515C-3.074 339.074 2.28 352 12.971 352zM288 64c17.645 0 32 14.355 32 32s-14.355 32-32 32-32-14.355-32-32 14.355-32 32-32z" fill="currentColor">
               </path>
              </svg>
             </div>
             <div class="content">
              <p>
               Vivamus eget aliquam dui.
              </p>
             </div>
            </div>
            <div class="features">
             <div class="icon">
              <svg aria-hidden="true" class="svg-inline--fa fa-archive fa-w-16" data-icon="archive" data-prefix="fas" focusable="false" role="img" viewbox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
               <path d="M32 448c0 17.7 14.3 32 32 32h384c17.7 0 32-14.3 32-32V160H32v288zm160-212c0-6.6 5.4-12 12-12h104c6.6 0 12 5.4 12 12v8c0 6.6-5.4 12-12 12H204c-6.6 0-12-5.4-12-12v-8zM480 32H32C14.3 32 0 46.3 0 64v48c0 8.8 7.2 16 16 16h480c8.8 0 16-7.2 16-16V64c0-17.7-14.3-32-32-32z" fill="currentColor">
               </path>
              </svg>
             </div>
             <div class="content">
              <p>
               Vivamus eget aliquam dui.
              </p>
             </div>
            </div>
           </div>
          </div>
         </div>
         <button>
          About us
         </button>
        </div>
       </section>
      </div>
     </main>
     <footer id="footer">
      <div class="footer-top">
       <div class="container">
        <div class="row">
         <div class="col-lg-3 col-sm-6 footer-links mx-auto">
          <h4 class="mb-3">
           DocEz
          </h4>
          <ul>
           <li>
            <a href="/about">
             About us
            </a>
           </li>
           <li>
            <a href="/contact">
             Contact us
            </a>
           </li>
           <li>
            <a href="/help">
             Help
            </a>
           </li>
           <li>
            <a class="ant-dropdown-trigger ant-dropdown-link">
             Select Theme
             <!-- -->
             <span aria-label="down" class="anticon anticon-down" role="img">
              <svg aria-hidden="true" data-icon="down" fill="currentColor" focusable="false" height="1em" viewbox="64 64 896 896" width="1em">
               <path d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
               </path>
              </svg>
             </span>
            </a>
           </li>
           <li>
            <div>
             <a class="ant-dropdown-trigger ant-dropdown-link">
              Select Language
              <!-- -->
              <span aria-label="down" class="anticon anticon-down" role="img">
               <svg aria-hidden="true" data-icon="down" fill="currentColor" focusable="false" height="1em" viewbox="64 64 896 896" width="1em">
                <path d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                </path>
               </svg>
              </span>
             </a>
            </div>
           </li>
          </ul>
         </div>
         <div class="col-lg-3 col-sm-6 footer-links mx-auto">
          <h4 class="mb-3">
           Policy Info
          </h4>
          <ul>
           <li>
            <a href="/privacy-policy">
             Privacy Policy
            </a>
           </li>
           <li>
            <a href="/terms-and-condition">
             Terms and condition
            </a>
           </li>
          </ul>
         </div>
         <div class="col-lg-3 col-sm-6 footer-contact mx-auto">
          <h4 class="mb-3">
           Our payment partners
          </h4>
          <div class="social-links">
           <a href="/" target="__blank">
            <img alt="American Express Logo" src="/images/footer-logos/american_express.png"/>
           </a>
           <a href="/" target="__blank">
            <img alt="Mastercard Logo" src="/images/footer-logos/mastercard.png"/>
           </a>
           <a href="/" target="__blank">
            <img alt="Amazon Pay Logo" src="/images/footer-logos/amazon_pay.png"/>
           </a>
           <a href="/" target="__blank">
            <img alt="Paytm Logo" src="/images/footer-logos/paytm.png"/>
           </a>
           <a href="/" target="__blank">
            <img alt="Gpay Logo" src="/images/footer-logos/gpay.png"/>
           </a>
          </div>
         </div>
        </div>
       </div>
      </div>
      <div class="container pb-4">
       <div class="copyright">
        <strong>
         � 2021 DocMz.
         <!-- -->
         All Rights Reserved
         <!-- -->
         .
        </strong>
       </div>
      </div>
     </footer>
    </div>
   </div>
  </div>
  <script id="__NEXT_DATA__" type="application/json">
   {"props":{"isServer":true,"initialState":{"user":{},"specialities":[],"doctors":{"all":[]},"dashboard":{"collapsed":false},"loggedInDoctor":{},"loggedInPatient":{"transactions":[]},"appointment":{},"sidebar":{"signin":false,"signup":false,"haslogin":false},"medicalHistoryAPI":{"reports":[],"medications":[],"appointments":[],"surgeries":[],"allergies":[]},"questionnaire":{"isAddingQuestion":false,"questionDetails":[],"questionnaireAdded":false,"error":"","gettingQuestionnaire":false,"questions":[],"errorGettingQuestionnaire":false},"ChatReducer":{"chatVisible":false,"videoCallVisible":{"show":false,"mode":"","User":{},"type":""},"UserInformation":{}},"WaitingRoom":{"WaitingAppointment":{},"UserDetails":{}},"referrer":{"referralUrl":null,"ambassadorId":null,"ambassadorUrl":null,"referralUrlId":null}},"initialProps":{"pageProps":{}}},"page":"/","query":{},"buildId":"eBb4pWLFo4uI9dGVUxHHZ","isFallback":false,"gip":true,"appGip":true}
  </script>
  <script nomodule="" src="/_next/static/chunks/polyfills-ba97178225fe6f84fb90.js">
  </script>
  <script async="" src="/_next/static/chunks/main-4e473b9358c28967fe67.js">
  </script>
  <script async="" src="/_next/static/chunks/webpack-aa403ce22e7aa0f354a1.js">
  </script>
  <script async="" src="/_next/static/chunks/framework.9fac7f60fdab795c24b8.js">
  </script>
  <script async="" src="/_next/static/chunks/cb1608f2.214663374522c8133134.js">
  </script>
  <script async="" src="/_next/static/chunks/75fc9c18.3e98bfd3653aed98df31.js">
  </script>
  <script async="" src="/_next/static/chunks/c86bb9a13864c97f4306d913b048d33e5d5628d7.d18b4cd5b9181f9df943.js">
  </script>
  <script async="" src="/_next/static/chunks/74997e99a3c5579caa2526e643d07fdbe156f62a.63bbb1a691a67ad33892.js">
  </script>
  <script async="" src="/_next/static/chunks/8aaefd24f6f471bcbddabb77ab483e809e275136.5a7d5f6f703692ea45f7.js">
  </script>
  <script async="" src="/_next/static/chunks/facd1ce66b42c18d3ee0f82ff803869cdff053df.9cfb233302fd661d19f9.js">
  </script>
  <script async="" src="/_next/static/chunks/9316a9feb24c5fc2c3f0aca9d93e100958f01eea.9952b0f8b7458ffbbdb9.js">
  </script>
  <script async="" src="/_next/static/chunks/002968e393e8c362597a6ffa918175194da586b6.999180cea4c6dc63131a.js">
  </script>
  <script async="" src="/_next/static/chunks/9ccc6e9a634ba6baae5b9bd3e51fb19f54e9a475.2982fe347b6c5794f4fe.js">
  </script>
  <script async="" src="/_next/static/chunks/1cb35f83e3404dc4e6c84c5c5f921b669fb7e1c9.0046728c71b6d6812323.js">
  </script>
  <script async="" src="/_next/static/chunks/c5dffeb90389c2d9d1ac64562a1a0c99ed325eb6.f6b2ff75076110131392.js">
  </script>
  <script async="" src="/_next/static/chunks/d15eab43bd30afb504a379ed209248cd3b4424cc.232a3d4c1105df92b496.js">
  </script>
  <script async="" src="/_next/static/chunks/a58409a16ca686574b149cb479cf9fae29db4027.c42310e3f3fe5355cc17.js">
  </script>
  <script async="" src="/_next/static/chunks/769993294b8f26110af2d0cafd87dba2e21939a0.2317aa61d36d98841d89.js">
  </script>
  <script async="" src="/_next/static/chunks/a97250b3cfd0241b16b47e1dd492fc33d76a869e.8bb3981cf392388cab41.js">
  </script>
  <script async="" src="/_next/static/chunks/ed42cf7cf4d127e28552aadc35e8384aa12e28c0.995b092053cbb134e175.js">
  </script>
  <script async="" src="/_next/static/chunks/2ad07823fd0ff8e9927ad17ef9337ddb1c92874c.471d6a87d0140aa19863.js">
  </script>
  <script async="" src="/_next/static/chunks/a20acd79148e99ca0424198d55a4e79070ed5d14.404cccb54f906c78322b.js">
  </script>
  <script async="" src="/_next/static/chunks/4822ecf71173a1d5d7545ee9312862fc5a4bfdf9.da33bdc577eb2eea01d6.js">
  </script>
  <script async="" src="/_next/static/chunks/59e023516f59ba2e6b1398e1d76344ed99e0f753.5de2c34f835d86e0dec1.js">
  </script>
  <script async="" src="/_next/static/chunks/e342705b3d0a23ab9db5c7cc876ac85177470104.8961cc40d5e29d1fc363.js">
  </script>
  <script async="" src="/_next/static/chunks/5825a58d163fd35f82e8d62eb2f8b239e5976d79.da4ff91fac4f409fa468.js">
  </script>
  <script async="" src="/_next/static/chunks/9d2e1ff9cc29387a0f12fc618b337bc50e1f1a08.b3c7fb29882e45a17159.js">
  </script>
  <script async="" src="/_next/static/chunks/styles.7dba968fc7c24df8bf27.js">
  </script>
  <script async="" src="/_next/static/chunks/pages/_app-38271f4f0af08c94ee77.js">
  </script>
  <script async="" src="/_next/static/chunks/79de5ff0.8553f0c9b32a5fb259e8.js">
  </script>
  <script async="" src="/_next/static/chunks/e8ba0c2e.5cce01f8b620a635bfe5.js">
  </script>
  <script async="" src="/_next/static/chunks/0192d2e8.f670b774c84bedcb2ff7.js">
  </script>
  <script async="" src="/_next/static/chunks/774383da.96a3f147dc1d4115bb99.js">
  </script>
  <script async="" src="/_next/static/chunks/46751129.8a4e5d9d6351c8c812e0.js">
  </script>
  <script async="" src="/_next/static/chunks/1a171660c3ba2a502c14fa6f6c6862c486f0235a.57e39ee8f9e99914d1f0.js">
  </script>
  <script async="" src="/_next/static/chunks/pages/index-fd0a25e04d5b97de951c.js">
  </script>
  <script async="" src="/_next/static/eBb4pWLFo4uI9dGVUxHHZ/_buildManifest.js">
  </script>
  <script async="" src="/_next/static/eBb4pWLFo4uI9dGVUxHHZ/_ssgManifest.js">
  </script>
 </body>
</html>
 
