# Adsbitvex SDK Integration

## 1️⃣ JavaScript SDK (HTML5 / Web Apps)

```html
<script src="https://bduegbqsqjghdltrkzbg.supabase.co/functions/v1/ad-script?appid=YOUR_APP_ID"></script>

<button onclick="showAd()">Show Reward Ad</button>

<script>
function showAd() {
  window.showadsbitvex()
    .then(() => { alert("Reward earned!"); })
    .catch(e => { alert("Ad failed"); });
}
</script>
