const navItems = document.querySelectorAll('.bottom-navigation a');

navItems.forEach(item => {
    item.addEventListener('click', () => {
        navItems.forEach(nav => nav.classList.remove('selected'));
        item.classList.add('selected');
    });
});