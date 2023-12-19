
# Yoga CLasses


This is  build to take
admission form for the Yoga Classes which happen every month.It is Build usin MERN stack(mongodb , Express , React.js,Node.js ).


## Approach

I have made a React form in which a user registration is made and user can give name, surname, age(age is validated between 18-65), 
and batch details. User is then directed to payments page where he can update payment status 
with Paynow button.The payment status is set false after every 30 days according to the joing day of the user(using Node-corn).Also the batch can be updated in every 30 days from the date of joing.The user can Login (using cookie authentication) to check the payment status and to make payments also to change the batch.

## API Reference

#### To authenticate

```http
  USE /api/auth
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `login details` | `string` | **Required**. Your id password |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |




## Demo



![image](https://github.com/Akash-Gottimukkala/Yoga-classes-main/assets/76110994/e8cb39fc-b607-493d-9e3f-94083c4c1dc6)
![image](https://github.com/Akash-Gottimukkala/Yoga-classes-main/assets/76110994/27dac27a-f12c-4030-82d0-d045c212b283)
![image](https://github.com/Akash-Gottimukkala/Yoga-classes-main/assets/76110994/70f3d722-2ed4-4fc1-ab18-1c9e9467fc76)

## ER Diagram 
![Screenshot 2023-12-18 221103](https://github.com/Akash-Gottimukkala/Yoga-classes-main/assets/76110994/80c47e6c-d572-462d-86b2-68a7ba8130c5)


