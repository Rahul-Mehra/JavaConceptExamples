
public class MultithreadingUsingThread extends Thread{

	public void run() {
		for(int i =1;i<6;i++) {
			try {
				System.out.println(i + " is demon "+isDaemon() );
				sleep(1000);
			} catch (InterruptedException e) {
				e.printStackTrace();
			}
		}
	}

	public static void main(String[] args) {
		MultithreadingUsingThread m1 = new MultithreadingUsingThread();
		MultithreadingUsingThread m2 = new MultithreadingUsingThread();
		m1.setDaemon(true);
		m1.start();
		m2.start();
	}
}
