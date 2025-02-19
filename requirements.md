# Функциональные требования

1. Система должна позволять регистрацию новых пользователей
2. Система должна производить авторизацию пользователей по логину и паролю
3. Система должна разделять пользователей на 4 роли в зависимости от предоставленных персональных данных и результатов их проверки.
4. Система должна предоставлять пользователям со статусом “Стартапер” возможность регистрации стартапов на платформе.
5. Основатель стартапа должен иметь возможность после регистрации стартапа на платформе публиковать на странице стартапа важные события, которые отражаются на работе над стартапом.
6. Система должна показывать на главной странице ленту с карточками зарегистрированных на платформе стартапов
7. Cистема должна предоставлять пользователю доступ к странице стартапа, с указанием названия, краткого описания, бизнес-плана, объеме собранных на платформе пожертвований, нанятых на платформе сотрудников, новостей стартапа.
8. Для всех зарегистрированных пользователей должна быть возможность жертвовать денежные средства в зарегистрированные на платформе стартапы, а также оставлять лайки и задавать вопросы на страницах стартапов.
9. Для пользователей с ролью “Соискатель” на странице стартапа должна быть возможность откликнуться на вакансии предлагаемые стартапом
10. У работодателя должна быть возможность принимать или отклонять заявки Соискателей в свои стартапы. При принятии заявки новый сотрудник должен отображаться на странице стартапа.
11. У трудоустроившихся на платформе Соискателей и их работодателей должна быть возможность выставлять друг другу оценки по 5-балльной шкале и писать друг о друге комментарии.
12.  Комментарии о стартапе должны отображаться на странице стартапа. 
13. Комментарии о Соискателе должны отображаться у Стартаперов, в стартапы которого подал заявку Соискатель вместе с заявкой Соискателя.
14. Система должна информировать Стартаперов о том, кто и какой объем средств пожертвовал в стартап этого Стартапера, а также позволять осуществлять связь между Стартапером и жертвователем.
15.  Система должна позволять Модераторам имеют доступ к специальному интерфейсу верификации введенных пользователями данных.
16. Система должна позволять Модераторам проверять введенные пользователям персональные данные перед одобрением повышения роли пользователя.
17. Система должна позволять Модераторам перед одобрение регистрации стартапа проверять введенные Стартапером данные.

# Нефункциональные требования

1. Новая учетная запись пользователя должна быть создана менее чем за 2000 мс
2. Система должна иметь не менее 99% доступности
3. Система должна обслуживать до 1000 одновременных пользователей
4. Система должна быть горизонтально масштабируемой для увеличения числа одновременных пользователей
5. Пользователь должен иметь возможность перейти на любую страницу сайта не более чем за 3 клика
