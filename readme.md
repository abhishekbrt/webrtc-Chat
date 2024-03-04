
# Webrtc-Chat

WebRTC Chat - Host/Guest is a simple yet powerful peer-to-peer chat application built using WebRTC technology. With just two HTML files, host.html and guest.html, users can easily establish secure, real-time communication channels between their devices.


# How to Use

1.Download host.html on one device and guest.html on another device.

2.Open host.html on the device you want to act as the host, and guest.html on the device you want to act as the guest.

3.In host.html, copy the SDP (Session Description Protocol) displayed and send it to the device with guest.html, using any method you prefer (e.g., WhatsApp, email).

4.In guest.html, paste the SDP received from the host into the designated field.

5.In guest.html, generate the SDP and copy it.

6.Send the copied SDP from guest.html back to the host (via WhatsApp, email, etc.).

7.In host.html, paste the SDP received from the guest into the designated field.

8.Congratulations! You're now connected and can start chatting directly.

# Limitations
Since only a STUN server is used, certain network environments, particularly those with strict NAT (Network Address Translation) policies or symmetric NAT configurations, may encounter difficulties establishing connections.