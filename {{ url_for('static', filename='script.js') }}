const submitButton = document.getElementById('submit');
const applicantNameInput = document.getElementById('name');
const resumeInput = document.getElementById('resume');

submitButton.addEventListener('mouseenter', () => {
    // Animate the button when the mouse enters
    submitButton.style.transform = 'scale(1.2)';
});

submitButton.addEventListener('mouseleave', () => {
    // Reset the button when the mouse leaves
    submitButton.style.transform = 'scale(1)';
});

submitButton.addEventListener('click', () => {
    if (applicantNameInput.value !== '' && resumeInput.value !== '') {
        // If the name and resume are filled, submit the form
        alert('Form Submitted');
    }
});

document.addEventListener('mousemove', (e) => {
    // Move the button to follow the mouse cursor
    const x = e.clientX - submitButton.offsetWidth / 2;
    const y = e.clientY - submitButton.offsetHeight / 2;
    submitButton.style.left = x + 'px';
    submitButton.style.top = y + 'px';
});

// Prevent the default form submission behavior
document.querySelector('form').addEventListener('submit', (e) => {
    e.preventDefault();
});
