<?php
session_start();
require_once 'config.php';

if (isset($_POST['submit'])) { // Assuming there's a submit button named 'submit'
    $Id = $_POST['name'];
    $password = password_hash($_POST['password'], PASSWORD_DEFAULT);

    $checkEmail = $conn->query("SELECT email FROM users WHERE email = '$email'");
    
    if ($checkEmail->num_rows > 0) {
        $_SESSION['register_error'] = 'Email is already registered!';
        $_SESSION['active_form'] = 'register';
    } else {
        $conn->query("INSERT INTO users (ID,  password,) VALUES ('$ID', '$password', )");
    }
    
    header('Location: index.php');
    exit();
}
?>

<?php
 
 if (isset($_POST['login'])) {
$ID = $_POST['ID'];
$password = $_POST['password'];

$result = $conn->query("SELECT * FROM users WHERE ID = '$ID'"); 
if ($result->num_rows > 0) {
    $user = $result->fetch_assoc();
    if (password_verify($password, $user['password'])) {
        $_SESSION['ID'] = $user['ID'];
        $_SESSION['password'] = $user['password'];


        if ($user['role'] === 'admin') { 
           header("Location: admin_page.php");
        } else {
             header("Location: user_page.php");
        }
        exit();
   }
}

$_SESSION['login_error'] = 'Incorrect Id or password';
$_SESSION['active_f'] = '';
header("Location: index.php");
exit();
}

?>