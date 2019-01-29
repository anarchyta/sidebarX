<h3>How to use?</h3>

<p>Add references to jQuery library and the jQuery sidebarX plugins files into the html page.</p>

<pre><code>&lt;link rel="stylesheet" href="assets/vendors/sidebarX.min.css"/&gt;
&lt;script type="text/javascript" src="assets/vendors/js/jquery.min.js"&gt;&lt;/script&gt;
&lt;script type="text/javascript" src="assets/vendors/js/bootstrap.min.js"&gt;&lt;/script&gt;
&lt;script type="text/javascript" src="assets/vendors/js/jquery.slimscroll.min.js"&gt;&lt;/script&gt;
&lt;script type="text/javascript" src="assets/sidebarX.min.js"&gt;&lt;/script&gt;</code></pre>

<p>You might need to load the Bootstrap Framework and Font Awesome icons.</p>

<pre><code>&lt;link rel="stylesheet" href="assets/vendors/css/bootstrap.min.css"/&gt;
&lt;link rel="stylesheet" href="assets/vendors/css/font-awesome.min.css"/&gt;</code></pre>

<h3>HTML Structured</h3>

<pre><code>&lt;!-- Page Sidebar --&gt;
&lt;div class=&#039;page-sidebar&#039;&gt;
  &lt;a class=&#039;logo-box&#039; href=&#039;index.html&#039;&gt;
  &lt;span&gt;Sidebar X&lt;/span&gt;
  &lt;i class=&#039;fa fa-lg fa-dot-circle-o&#039; id=&#039;fixed-sidebar-toggle-button&#039;&gt;&lt;/i&gt;
  &lt;i class=&#039;fa fa-lg fa-close&#039; id=&#039;sidebar-toggle-button-close&#039;&gt;&lt;/i&gt;
  &lt;/a&gt;
  &lt;div class=&#039;page-sidebar-inner&#039;&gt;
    &lt;div class=&#039;page-sidebar-menu&#039;&gt;
      &lt;ul class=&#039;accordion-menu&#039;&gt;
        &lt;!-- Active Page --&gt;
        &lt;li class=&#039;active-page&#039;&gt;
          &lt;a href=&#039;#&#039;&gt;&lt;i class=&#039;fa fa-home&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Dashboard&lt;/span&gt;&lt;/a&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;#&#039;&gt;&lt;i class=&#039;fa fa-envelope&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Email&lt;/span&gt;&lt;/a&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;javascript:void(0)&#039;&gt;&lt;i class=&#039;fa fa-underline&#039;&gt;&lt;/i&gt;
          &lt;span&gt;UI Kits&lt;/span&gt;&lt;i class=&#039;accordion-icon fa fa-angle-left&#039;&gt;&lt;/i&gt;&lt;/a&gt;
          &lt;ul class=&#039;sub-menu&#039;&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Alerts&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Buttons&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Icons&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Typography&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Notifications&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Modals&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Progress Bars&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Tabs &amp; Accordions&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Tree View&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Nestable&lt;/a&gt;&lt;/li&gt;
          &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;javascript:void(0)&#039;&gt;&lt;i class=&#039;fa fa-th&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Layouts&lt;/span&gt;&lt;i class=&#039;accordion-icon fa fa-angle-left&#039;&gt;&lt;/i&gt;&lt;/a&gt;
          &lt;ul class=&#039;sub-menu&#039;&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Blank Page&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Boxed Layout&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Collapsed Sidebar&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Fixed Header&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Fixed Sidebar&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Fixed Sidebar &amp; Header&lt;/a&gt;&lt;/li&gt;
          &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;javascript:void(0)&#039;&gt;&lt;i class=&#039;fa fa-wpforms&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Forms&lt;/span&gt;&lt;i class=&#039;accordion-icon fa fa-angle-left&#039;&gt;&lt;/i&gt;&lt;/a&gt;
          &lt;ul class=&#039;sub-menu&#039;&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Elements&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Form Wizard&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;File Upload&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Image Crop&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Image Zoom&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;X-editable&lt;/a&gt;&lt;/li&gt;
          &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;javascript:void(0)&#039;&gt;&lt;i class=&#039;fa fa-table&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Tables&lt;/span&gt;&lt;i class=&#039;accordion-icon fa fa-angle-left&#039;&gt;&lt;/i&gt;&lt;/a&gt;
          &lt;ul class=&#039;sub-menu&#039;&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Static&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Responsive&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Data Tables&lt;/a&gt;&lt;/li&gt;
          &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;#&#039;&gt;&lt;i class=&#039;fa fa-pie-chart&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Charts&lt;/span&gt;&lt;/a&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;javascript:void(0)&#039;&gt;&lt;i class=&#039;fa fa-location-arrow&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Maps&lt;/span&gt;&lt;i class=&#039;accordion-icon fa fa-angle-left&#039;&gt;&lt;/i&gt;&lt;/a&gt;
          &lt;ul class=&#039;sub-menu&#039;&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Google&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Vector&lt;/a&gt;&lt;/li&gt;
          &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;javascript:void(0)&#039;&gt;&lt;i class=&#039;fa fa-gem&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Extra&lt;/span&gt;&lt;i class=&#039;accordion-icon fa fa-angle-left&#039;&gt;&lt;/i&gt;&lt;/a&gt;
          &lt;ul class=&#039;sub-menu&#039;&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Invoice&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;404 Page&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;500 Page&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Profile&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Login&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Register&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Lockscreen&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Todo&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Gallery&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Pricing Tables&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&#039;#&#039;&gt;Timeline&lt;/a&gt;&lt;/li&gt;
          &lt;/ul&gt;
        &lt;/li&gt;
        &lt;li class=&#039;menu-divider&#039;&gt;&lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;#&#039;&gt;&lt;i class=&#039;fa fa-cogs&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Documentation&lt;/span&gt;&lt;/a&gt;
        &lt;/li&gt;
        &lt;li&gt;
          &lt;a href=&#039;#&#039;&gt;&lt;i class=&#039;fa fa-support&#039;&gt;&lt;/i&gt;
          &lt;span&gt;Changelog&lt;/span&gt;&lt;span class=&#039;label label-danger&#039;&gt;1.0&lt;/span&gt;&lt;/a&gt;
        &lt;/li&gt;
      &lt;/ul&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
&lt;!-- /Page Sidebar --&gt;</code></pre>

<h3>Variable Options <small>Initialize the plugin and we're done.</small></h3>

<pre><code>$(document).sidebarX({
      submenu_animation_speed: 100,
      submenu_opacity_animation: true,
      page_boxed: false,
      page_header_fixed: false,
      page_sidebar_fixed: false
      page_sidebar_collapsed: false
});</code></pre>
