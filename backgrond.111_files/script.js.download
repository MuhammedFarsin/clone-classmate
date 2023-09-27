function hideMenu(){
  const ul = document.querySelector('ul');
  ul.style.right= '-170px';
  ul.style.transition = '1s';
}
function showMenu(){
const ul = document.querySelector('ul');
ul.style.right = '0';
ul.style.transition = '1s';
}
function addDarkmodeWidget() {
    new Darkmode().showWidget();
  }
  const options = {
    bottom: '64px', // default: '32px'
    right: 'unset', // default: '32px'
    left: '32px', // default: 'unset'
    time: '0.5s', // default: '0.3s'
    mixColor: '#fff', // default: '#fff'
    backgroundColor: '#fff',  // default: '#fff'
    buttonColorDark: '#100f2c',  // default: '#100f2c'
    buttonColorLight: '#fff', // default: '#fff'
    saveInCookies: false, // default: true,
    label: '🌓', // default: ''
    autoMatchOsTheme: true // default: true
  }
  
  const darkmode = new Darkmode(options);
  darkmode.showWidget();
  window.addEventListener('load', addDarkmodeWidget);
  $(window).on("load",function(){
    $(".loader-wrapper").fadeOut("slow");
  });