1. $('.profile-image').attr('src', "http://placekitten.com/g/400/400");

1b. $('#left-image img').attr('src', "http://placekitten.com/g/325/225");

2. $('h1.highlight').text('Justin C');

3. $('#employment .info-title').text('Hobbies and thangs');

4. $('#time-travel').parent().remove();

5. $('body').css('color', 'aquamarine');

6. $('.highlight').css('color', 'salmon');

7. $('h1').css('font-family', 'monospace');

8. $('.action-icon-bg').css('background-color', 'blue');

9. $('#name').attr('placeholder', 'Identify Yourself');

10. $('#message').attr('placeholder', 'State your business');

11. $('#name').attr('value', 'Your Nemesis');

12. $('#email').attr('value', 'koalathebear@gmail.com');

13. $('#submit').attr('value', 'En Garde!');

14. $('#submit').attr('disabled', true);

15. $('.bio-info').empty();

Adding elements to DOM

1. $('#right-image img').clone().appendTo('form');

2. for (var i=0; i < 10; i++) { $('#right-image img').clone().appendTo('form'); };
