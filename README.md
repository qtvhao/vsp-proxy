# vsp-proxy
📊 Video sharing platform - Proxies Diagram (Revised) 📊

### 📊 ** Proxies Diagram (Revised)** 📊

``` 
          [Main Server]
                   |
                   ↓
          [Transcoding Proxy]
                   |
          (Converts videos into multiple formats & resolutions)
                   ↓
               [Reverse Proxy]
                   |
   (Manages traffic, security, and load balancing)
                   ↓
------------------------------------------
|                  CDN Proxy                |
------------------------------------------
                   |
      (Stores video copies worldwide)
                   ↓
             [Caching Proxy]
                   |
  (Temporarily stores popular videos for quick access)
                   ↓
------------------------------------------
|            Edge Proxy Servers            |
------------------------------------------
                   |
        (Handles requests from nearby users)
                   ↓
         [Adaptive Bitrate (ABR) Proxy]
                   |
  (Adjusts video quality based on user’s internet speed)
                   ↓
           [User Device (Laptop, Mobile, TV)]
```

### 💡 **Explanation** 💡

1. **Main Server** 🖥️: Stores all original video data and manages the system.
2. **Transcoding Proxy** 🎥: Converts videos into various formats and resolutions.
3. **Reverse Proxy** 🔄: Manages incoming user requests, balancing the load and adding security.
4. **CDN Proxy** 🌐: Delivers video copies from servers closer to the user, making streaming faster.
5. **Caching Proxy** 🗂️: Temporarily holds frequently accessed videos to reduce loading times.
6. **Edge Proxy Servers** 📍: Provide local delivery of content to nearby users.
7. **ABR Proxy** 📶: Adjusts the video quality based on internet speed, ensuring smooth playback.

