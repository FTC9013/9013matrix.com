navigator.serviceWorker.register('/service-worker.js')
    .then(registration => {
        console.log('Service Worker registered:', registration);
    });
