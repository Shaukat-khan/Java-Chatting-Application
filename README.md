# Java-Chatting-Application
Created a Java Chatting Application using java core, swing and socket programming 

## What it does
We have two tabs open for two people chatting with one another. Just like a real chatting app in this we have a bar for typing our messages and sending them. When I send a message for me it shows it on the right and for the person that received it, shows my message on the left of the screen. Everytime the other chatter is typing it says their name and shows with it "is typing...". Once they stop typing it stops showing. 

## Classes
We had to create two classes, one called server and the other client. Both classes would be able to talk with each other through the application as long as they wanted. We added a scroll bar so that we can see the whole conversation between both of them. Both classes were almost the same just a couple of differences but all the packages we needed were the same. As you can see below we need every single detail to make it look as real and attractive as possible. 

## Imported packages
import java.awt.BorderLayout;
import java.awt.Color;
import java.awt.Font;
import java.awt.Image;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.awt.event.KeyAdapter;
import java.awt.event.KeyEvent;
import java.awt.event.MouseAdapter;
import java.awt.event.MouseEvent;
import java.io.DataInputStream;
import java.io.DataOutputStream;
import java.net.Socket;
import java.text.SimpleDateFormat;
import java.util.Calendar;
import javax.swing.BorderFactory;
import javax.swing.Box;
import javax.swing.BoxLayout;
import javax.swing.ImageIcon;
import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JPanel;
import javax.swing.JScrollPane;
import javax.swing.JTextField;
import javax.swing.Timer;
import javax.swing.border.EmptyBorder;
