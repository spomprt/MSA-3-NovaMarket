| Этап                                   | Тип события  | Название                |
|----------------------------------------|--------------|-------------------------|
| Заказ подтвержден                      | domain       | OrderConfirmed          |
| Заказ успешен                          | domain       | OrderSucceeded          |
| Заказ отменен                          | failure      | OrderFailed             |
| Резервация товара                      | domain       | ProductsReserved        |
| Резервация не прошла                   | failure      | ReservationFailed       |
| Резервация отменена                    | compensation | ReservationCancelled    |
| Оплата проведена                       | domain       | PaymentSucceeded        |
| Оплата не прошла                       | failure      | PaymentFailed           |
| Возврат денежных средств               | compensation | RefundSucceeded         |
| Заявка в службе логистики сформирована | domain       | ShippingRequestCreated  |
| Отказ логистики по заявке              | failure      | ShippingRequestRejected |
| Уведомление отправлено пользователю    | domain       | ClientNotified          |
| Уведомление отправлено продавцу        | domain       | SellerNotified          |
