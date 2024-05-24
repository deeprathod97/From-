let form = document.getElementById('myForm');

form.addEventListener('submit', (event) => {
  event.preventDefault();
  let name = document.getElementById('name').value;
  let email = document.getElementById('email').value;
  let phone = document.getElementById('phone').value;
  let password = document.getElementById('password').value;


  if (name === '') {
    alert('Name is required');
    return;
  }

  
  if (!/^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/.test(email)) {
    alert('Invalid email address');
    return;
  }

  
  if (!/^\d{10}$/.test(phone)) {
    alert('Invalid phone number');
    return;
  }


  if (password.length < 8) {
    alert('Password must be at least 8 characters');
    return;
  }


  form.submit();
});