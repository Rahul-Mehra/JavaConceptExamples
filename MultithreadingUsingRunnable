public class MultithreadingUsingRunnable implements Runnable {
	public void run() {
		for(int i =1;i<6;i++) {
			try {
				System.out.println(i);
				Thread.sleep(1000);
			} catch (InterruptedException e) {
				e.printStackTrace();
			}
		}
	}

	public static void main(String[] args) {
		MultithreadingUsingRunnable m1 = new MultithreadingUsingRunnable();
		MultithreadingUsingRunnable m2 = new MultithreadingUsingRunnable();

		Thread t1 = new Thread(m1);
		Thread t2 = new Thread(m2);

		t1.setDaemon(true);
		t1.start();
		t2.start();
	}
}
