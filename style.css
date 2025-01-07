
// Voice Guidance System
document.getElementById("voiceButton").addEventListener("click", () => {
    const message = new SpeechSynthesisUtterance("Welcome to the Dashboard. Use the referral link to invite friends.");
    window.speechSynthesis.speak(message);
});

// Copy Referral Link
function copyReferral() {
    const link = document.getElementById("referralLink").innerText;
    navigator.clipboard.writeText(link).then(() => {
        alert("Referral link copied to clipboard!");
    }).catch(err => {
        console.error("Failed to copy link: ", err);
    });
}

// Password Validation
function validatePassword() {
    const password = document.getElementById("passwordInput").value;
    const warningMessage = document.getElementById("warningMessage");

    if (password.length < 6) {
        warningMessage.textContent = "Password must be at least 6 characters long.";
        warningMessage.style.color = "red";
    } else {
        warningMessage.textContent = "Password looks good!";
        warningMessage.style.color = "green";
    }
}
