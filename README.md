import React from "react";

export default function CanvasLanding() {
  return (
    <div className="h-screen bg-black flex items-center justify-center p-6">
      <video loop autoPlay muted className="h-full max-h-full w-1/2 rounded-xl shadow-lg">
        <source src="/videos/WELCOME_BONUS_UP_TO_100.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
    </div>
  );
}
