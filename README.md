<script>
  const username = "Dqrkky";

  // Create <a>
  const link = document.createElement("a");
  link.href = `https://github.com/${username}?tab=repositories`;
  link.style.position = "absolute";
  link.style.top = "38%";
  link.style.left = "58%";
  
  // Create <img>
  const img = document.createElement("img");
  img.src = `https://githubreadmestats-fork.vercel.app/api/top-langs/?username=${username}&layout=pie&theme=dark`;
  
  // Append img → a → body
  link.appendChild(img);
  document.body.appendChild(link);

</script>
